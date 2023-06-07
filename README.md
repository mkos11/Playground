# Playground
Another pure masterpiece from FPHam, Text WebUI extension to add clever multi-Notebook TAB to Chat mode

![image](https://github.com/FartyPants/Playground/assets/23346289/5556d53e-03cd-4c5f-abbb-03c0bd52e974)

You have two independent Notebooks that are always present, regardless of the mode.
You can explore variations and try many new things.
You can type in one while the other is generating.

But wait, that's not all!

No. 

The notebooks can enable Quick Instruct mode, where --- (three dashes) signal the line is an instruct (and will be hence formatted accordingly to User/bot prompt)

![image](https://github.com/FartyPants/Playground/assets/23346289/9320a2ec-9d17-45f7-936a-567cd0531447)

if you just type a question such as:
```
What is another word for happy?
```
the LLM may likely answer in another question:
```
What is another word for happy?
In what way did the Great Depression affect American families and the government?
```
but if you prepend three dashes
```
--- What is another word for happy?
```
this now means the line is an instruct and the LLM will respond according to it's fine tune
```
--- What is another word for happy?
 There are many words that can be used to describe happiness, such as joyful, ecstatic, elated or delighted.
 ```
 
 Similarly you can give a followup instructions:
 
 Once upon a time in a land not so far away there lived a young lad called Jack who was very good at his job. One day while walking through the forest he stumbled across an old man sitting by a stream, looking tired and hungry. 
```
--- Make the above text sound much funnier
 Once upon a time in a fantasy world where unicorns roam free and rainbows arch over crystal-clear waterfalls, there once was a hero named Jack. While on a quest to save a damsel in distress from an evil dragon, he accidentally fell into a pit of mushrooms which sent him on an acid trip unlike any other.
```

Other interesting thing is that yyou may just simply change the User/Bot prompts and see how the response changes!

So you have both the instruct mode AND the flexibility of notebook.

Am I clever or what?




