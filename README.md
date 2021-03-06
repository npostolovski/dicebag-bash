## Dicebag 

A simple Bash script you can use to roll standard tabletop RPG die (d4, d6, d8, d10, d12, d20) via the command line. Integration tests utilise the [shunit2](https://code.google.com/archive/p/shunit2/downloads) library.

![Dicebag](https://github.com/npostolovski/dicebag-bash/blob/master/dicebag.jpg)

#### Usage

```
./roll.sh d20

#=> 6
```

You may wish to alias the script in your `.bashrc` as follows:

```
roll () {
  <path to roll.sh> $1
}
```

This will allow the following usage:

```
roll d20

#=> 17
```

#### Why?

This ridiculously simple Bash script was created as a way for me to practice my Bash scripting skills. I also enjoy creating CLI tools that do one tiny, marginally useful thing well.
