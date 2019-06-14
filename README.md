# NepaliPoem-Net
Generates poem(Nepali)  from given word/group of word/character.

It is like teaching a network about characters 'क', 'ख'... and teaching what character constitues to form a poem. Training the model with the large corpus of text(poems) compiled from different sources in internet, it learns a probabilistic model about what character comes after the given sequence of character, store the generated character and again use it to predict the next character till it compose a poem. 

The notebook is downloaded from Google Colab and the model is trained in a GPU available in colab, so it may not work in some CPU.

**Uses**

* numpy
* tensorflow

**Demo**

![](https://github.com/PrasangaDhungel/NepaliPoem-Net/blob/master/demo.png)
