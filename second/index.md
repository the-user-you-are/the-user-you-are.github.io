# Module oriented model in word processing

## Text paragraph modules

### simple formatting - markdown

#### To create paragraphs, use a blank line to separate one or more lines of text:

First paragraph: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Second paragraph: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

#### To create a line break (`<br>`), end a line with two or more spaces, and then type return.

My paragraph:  
Lorem ipsum dolor sit amet, consectetur adipiscing elit,  
sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

#### Emphasis

You can add emphasis by making text bold or italic.  
To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

__My paragraph:__  
L**o**rem ipsum d**o**l**o**r sit amet, c**o**nsectetur adipiscing elit,  
sed __do__ eiusmod tempor incididunt __ut__ labore __et__ dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

```md
__My paragraph:__  
L**o**rem ipsum d**o**l**o**r sit amet, c**o**nsectetur adipiscing elit,  
sed __do__ eiusmod tempor incididunt __ut__ labore __et__ dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
```

To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

_My paragraph:_  
L*o*rem ipsum d*o*l*o*r sit amet, c*o*nsectetur adipiscing elit,  
sed _do_ eiusmod tempor incididunt _ut_ labore _et_ dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

```md
_My paragraph:_  
L*o*rem ipsum d*o*l*o*r sit amet, c*o*nsectetur adipiscing elit,  
sed _do_ eiusmod tempor incididunt _ut_ labore _et_ dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
```
To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase. To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.

___My paragraph:___  
L***o***rem ipsum d***o***l***o***r sit amet, c***o***nsectetur adipiscing elit,  
sed ___do___ eiusmod tempor incididunt ___ut___ labore ___et___ dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

```md
___My paragraph:___  
L***o***rem ipsum d***o***l***o***r sit amet, c***o***nsectetur adipiscing elit,  
sed ___do___ eiusmod tempor incididunt ___ut___ labore ___et___ dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
```

### simple formatting - html

#### text-align center

```html
<p style="text-align: center;">center</p>
```

<p style="text-align: center;">center</p>
  
#### text-align right

```html
<p style="text-align: right;">right</p>
```
<p style="text-align: right;">right</p>

#### text-align justify

```html
<p style="text-align: justify;">
  Lorem ipsum...
</p>
```

<p style="text-align: justify;">
My paragraph: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</p>

#### line break (`<br>`)

```html
<p style="text-align: right;">
My paragraph:<br> Lorem ipsum dolor sit amet, consectetur adipiscing elit,<br> sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.<br> Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</p>
```

<p style="text-align: right;">
My paragraph:<br> Lorem ipsum dolor sit amet, consectetur adipiscing elit,<br> sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.<br> Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</p>

#### bold and italics

```html
<p style="text-align: justify;">
<b><i>My paragraph:</i></b><br> L<b>o</b>rem ipsum d<b>o</b>l<b>o</b>r sit amet, consectetur adipiscing elit,<br> sed <i>do</i> eiusmod tempor incididunt <i>ut</i> labore <i>et</i> dolore magna aliqua.<br> Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</p>
```

<p style="text-align: justify;">
<b><i>My paragraph:</i></b><br> L<b>o</b>rem ipsum d<b>o</b>l<b>o</b>r sit amet, consectetur adipiscing elit,<br> sed <i>do</i> eiusmod tempor incididunt <i>ut</i> labore <i>et</i> dolore magna aliqua.<br> Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</p>

## Image in paragraph modules

### modules with image - markdown

#### Insert image

```md
![Image](https://... "My image")
```

![Image](hill.jpg "My image")


### modules with image - html

#### default

<img src="hill.jpg" alt="hill" title="hill" />

