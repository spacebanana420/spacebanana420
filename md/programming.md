# Programming Overview

Programming and general operating system tinkering/administration is one of my main activities.
I like to make CLI programs that solve my practical necessities. Sometimes (though rarely) I also make TUI programs.

I started programming years ago when I wanted to make games for fun.
Between 2014 and 2019, I went through the pipeline: Roblox + Lua => Unity + Javascript => Unity + C#.
Eventually I halted programming due to a decreasing interest in game dev.
After finishing high school in 2021 I decided to give Linux a try for the first time, and that opened a vast world for programming and my interest resumed very quickly.

## The Drive

Different kinds of people have different interests, desires and motivations in programming, and I have my own.
My programming motivation is extremely practical, having a huge focus on developing tools that solve problems or automate solutions in my daily computer use.
I enjoy programming a lot, but if the necessity isn't there then the motivation and initiative won't be either.
The instant I have a reason to get my hands on the keyboard I will and because of this, I tend to use the programs I make extremely often.

For example, I use my Nitori and Aya every day, almost every hour, and I build my own projects with my Yuuka build tool.
I use my Parasol file manager mainly for browsing and playing music every day too.
When I used Geany for programming, I made a simple program for colour-grading existing Geany themes.

The practical drive makes you build tools that you use very often, but at the cost of not wanting to program if the necessity is not there.
And so, programming to me is more of a means to an end, even though I love when I get my hands dirty.

## Software Minimalism

I am a minimalist with strong opinions about how I should program and how my programs should be.

I'm not an anti-bloat extremist but I do enjoy software performance, minimalism and simplicity.
Hardware is faster than ever as time passes and yet software in a general sense is slower and more overcomplicated than ever, especially proprietary software.

A lot of programs follow a more minimalist path which I enjoy, and performance isn't the only benefit.
Simplicity, autonomy and efficiency also tend to be caused by minimalism among other qualities.

For many kinds of tasks, a CLI program is simpler, faster and more efficient to use once you know its arguments than a huge and slow GUI.
There are cases of course where a graphical application is much better or even the only option, but whenever possible I like to use CLI or TUI counterparts if I feel that they are more efficient.

## UNIX

I follow UNIX software and operating system design very closely. UNIX is revolutionary and visionary, it completely changed how we use and control a computer and in a way it changed my life.

* Modularity and composability provide freedom to choose and manipulate the various components of your operating system. You can also compose programs together (piping) regardless of API or ABI, since STDOUT, STDERR and STDIN are universal.
* Text as the universal language is very good for the human and the program. Text-based interfaces and data are agnostic to all programming languages and also let the user manipulate the contents directly. You can cat and grep, or open with a text editor, or script it or even program around it.
* Simplicity of "do one thing and do it well" mixes well with the modularity and composability I mentioned earlier.
* Pseudo-files are an incredible way to interact with the hardware and kernel. Instead of being bound to raw system calls or a language-specific API, pseudo-files allow you to read hardware and kernel data as well as send instructions to the kernel which can then configure or change the behaviour of hardware and the core components of the system. Since it's disguised as file operations, despite having 0 disk activity, it's an interface that can be interacted with any programming language, environment, text editor or simple manual intervention.

This software and OS design empowers autonomy, freedom, control, efficiency and the initiative to do things yourself directly with little friction.

## Languages

My opinions and preferences on programming languages are very established. I tend to like static-typed languages that look C-like or similar but have quality of life and (semi) modern features.
Boring languages that let me do whatever I want a proper way is something I appreciate.

* I like using Java the most. I use and abuse this language every time I can and I'm very experienced in it.
* I also like C# though I only really use it on Unity since Java covers the rest.
* I don't currently use Go but I really admire this language and the pure efficiency and simplicity and cross-complication capability. Go masters practicality and simplicity and I might switch to it one day.
* Ruby is nice, I tend to avoid dynamically-typed languages but I like it especially for automation and small tools.
* I use Python all the time at work but I don't like how it's designed and how pip enforces overcomplicated virtual environments to install libraries system-wide. I prefer Ruby for personal use.
* I tend to avoid pure functional programming languages or languages that are closer to it, such as Haskell. I prefer direct imperative programming that doesn't get in my way and is the most transparent.

## Environment

I currently use GNU Emacs, Helix and Micro for programming. I used all kinds of editors before and I might change to another one in the future but for now I'm established.

I like to use tools that are very cross-platform or entirely platform-agnostic, tools that I know will always be there for me even if I drastically switch platform or environment one day.
I don't like big IDEs, not as much because of their size and slowness (though that too) but mostly because they are designed for all your functionality and tools to be inside them.
When a single editor contains everything, including compiler/build tool, terminal, git, etc, you become bound to it.
Being bound to an IDE makes it much harder to replace a component, since you have to replace the entire suite or stay exactly the same.
Fragmentation provides modularity, then you can swap certain tools while keeping others and you can cherrypick the various tools that compose your environment.

## Documentation

I love good documentation and I have a very strong standard for what good documentation is.
A good example of great documentation is the Java and .NET API documentation: Easy to find what you want, everything is structured linearly and logically, everything is transparent. All the methods, fields, static or not, what is returned, what exceptions it can throw, description, example, etc is very well laid out.

I heard many programmers hate writing documentation, but I love writing my own. I believe it's very important that everything I make is well-documented both for the user and the developer, even for myself.
At the very least I should write comments in code if documentation isn't there.
