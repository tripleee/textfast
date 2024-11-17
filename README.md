# TextFast
Have you aver felt bored from typing longs and tedious words or sentences
every time when you want to reply a chat or created a post in Reddit?
This addon is for you.
It helps you type fast in a very customizable way in the browser.

You can create shortcuts for words, sentences, or emoji,
and then type them in the browser and write really fast.
For instance: you can transform the phrase "I'm coming" into a shortcut "imc"
and every time you time "imc" you will get "I'm coming".
Another one? You can transform "shrug" into "¯\\_[ツ]_/¯"
and then you will never mess up with the characters ever again.

All you have to do is to enter the configuration page (click the icon)
and create a unique style of writing to you and then save it, and that is it.

Good Luck, Have fun (typed: glhf)

## Why?

Well, I'm lazy to type and I don't like to type too much,
so I want to be able to type fast even in Firefox and
all the websites that I use.


## Configuration

When you install the addon, it will add a new icon to the top bar.
Click there and you will be in the "configuration page"
(I'll improve that, I hope, I'm not very good at design).
Then, click the "+" (plus) icon and it will create a new row in the list.
Now, in the "Replace" column you will put a shortcut for your boring
word, sentence, or emoji,
and in the "With" you will put the real word / sentence / emoji;
and then, click Save.
That is it, now go to google and just test it, and then add more shortcuts.

![Configuration Page](/screenshot.png)

### Import 

For advanced users or if you exported the list from other installation
For those who don't want to add shortcuts one by one,
you can create a JSON file following [`example.json`](example.json)
with your words and just import it and **save** it.

```
[ {"replace": "foo", "with": "bar"},
  {"replace": "baz", "with": "quux"}]
```

## Browsers

For now, I'm only focusing on Firefox + webext.
But it will be cool to port it to other browsers.

## TODO

- [x] Support dynamic inputs
- [ ] Support non-usual way to enter a text
- [x] Improve the UI of the list
- [ ] Use a better icon
- [ ] Sync your list with all your browsers
- [ ] Change the name (maybe)

## Do you want to help?

See the TODO list and talk to me, I'm open to new ideas.
