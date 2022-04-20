
***

![/PrologLogo1.png](/PrologLogo1.png)

# Learning Prolog

## 2021 Basic syntax (prolog)

Testing basic syntax of Prolog

```prolog
% Start of script
% The main script for the Kiri voice assistant
% Read from primary libraries
read from "///kiri/LIBraries/voice-commands/1/", nl.
read from "///kiri/LIBraries/ENGINE.pl", nl.
% Main
?- write('Hello, what can I help you with?'), nl.
wait for response, nl.
if no response in 10, nl.
  exit, nl.
  break, nl.
else, nl.
break, nl.
?-
% File info
% File type: Prolog source file (*.pl) Not to be confused with Perl/Raku
% File version: 1 (Monday, 2021 September 27th at 6:03 pm)
% Line count (including blank lines and compiler line): 21

% End of script
```

This is source code from the main thread of V1 of the [Kiri](https://github.com/seanpm2001/Kiri/) project, which is part of the [WacOS Operating system project](https://github.com/seanpm2001/WacOS/wiki/Kiri/) this script likely does not work at all, it worked very poorly for me, as the syntax kept changing from Perl to Prolog and Prolog to Perl, and I couldn't get the language down due to the confusion. - 2021 Monday, September 27th

**This section was last updated on 2021, Tuesday, October 5th at 12:19 am**

## Comments in Prolog

These are comments in Prolog.

```prolog
% This is a comment
```

## Break keyword in Prolog

```prolog
break;
```

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

## File extension problem

Prolog and Perl both share the `*.pl` file extension. This didn't work out too well with me recently, and I have decided upon changing my Prolog files to the *.pro file extension supplied by Prolog. - 2021 September 29th

### Possible solution

Prolog seems to support the `*.pro` file extension as well, I will be using it instead.

***

# Other knowledge of Prolog

1. Prolog is a programming language commonly used for Artificial Intelligence and speech synthesis.

2. Prolog is not a curly bracket and semicolon language

3. Prolog uses the `*.P`, `*.pl`, and `*.pro` file extensions

4. Prolog is a programming language that contains limitations

5. Prolog has existed since the year 1972

6. I am not sure whether Prolog is an open source programming language or not

7. No other knowledge of the Prolog programming language at the moment.

***

**File version:** `1 (2022, Wednesday, April 20th at 4:10 pm PST)`

***
