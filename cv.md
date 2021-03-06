## Personal data

**Name:** Timur Sarsymbaev

**Date of Birth:** 14/11/2001

**Location:** Belarus, Mogilev

**Mobile:** 80298930736

**E-mail:** sarsymbaef@yandex.by

**LinkedIn:** https://www.linkedin.com/in/timur-sarsymbaev-09721a1b0/


## Technical skills
* C#
* JS
* HTML, CSS, React
* GitHub
* Visual Studio, Visual Studio Code, Webstorm


## Lenguages
* English - Pre-Intermediate (I improve my skills every day)
* Russian - Native speaker
* Belarussian - Native speaker


## Some facts about me
I like do sports like footbal, table tennis.

I am free of the bad habits.

In free time, I like to watch videos on youtube about game dev

I can find the best solution to the problem in a short period of time.


## Education
* 2019 - 2023 / Belarusian-Russian Uiversity / 	Automated Data Processing Systems (Information Technologies Engineer) / Mogilev, Belarus
* 2020 - now / Aspect lenguage center / Pre-Intermediate course (Engleash)



## Code example
```C#
            Program prog = new Program();
            int x = 9, y = 0, health = 10;
            int[,] bombs = new int[10, 10];
            prog.Bombs(bombs);
            try
            {
                while (x != -1)
                {
                    prog.View(prog.Field(x, y), health);
                    prog.Сontrol(ref x, ref y);
                    prog.Boom(bombs, ref health, x, y);
                    Console.Clear();
                    if (prog.Congratulations(ref x, ref y, ref health)) break;
                }
            }
            catch
            {
                throw new ArgumentNullException("Field", "cannot be displayed");
            }
```
