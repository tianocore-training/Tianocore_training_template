---?image=assets/images/gitpitch-audience.jpg
@title[Tianocore Open Source Training contents]
<br><br>
<span style="font-size:0.75em" >This slide deck has moved to:  https://gitpitch.com/tianocore-training/Tianocore_training_template/master#/</span>
<br><br><br>
## <span class="gold"   >UEFI & EDK II Training</span>

#### Template 

<br>
<span style="font-size:0.75em" ><a href='http://www.tianocore.org'>tianocore.org</a></span>
Note:
  PITCHME.md for UEFI / EDK II Training  template slide show 

  Copyright (c) 2018, Intel Corporation. All rights reserved.<BR>

  Redistribution and use in source (original document form) and 'compiled'
  forms (converted to PDF, epub, HTML and other formats) with or without
  modification, are permitted provided that the following conditions are met:

  1) Redistributions of source code (original document form) must retain the
     above copyright notice, this list of conditions and the following
     disclaimer as the first lines of this file unmodified.

  2) Redistributions in compiled form (transformed to other DTDs, converted to
     PDF, epub, HTML and other formats) must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR
  IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
  EVENT SHALL TIANOCORE PROJECT  BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
  SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

---
@title[Speaker notes]
### <p align="center"<span class="gold"   >Add Speaker Notes </span></p>
<span style="font-size:0.9em">
Speaker notes can be added by using key word "Note:" in the <b>PITCHME.md</b> file after defining the slide content
</span>

- must be after all slide markdown
- show up in the speaker notes 
- use key "S" to display speaker notes during slide show
- uses markdown 

Note:

## using the "Note:" tag keyword
- must be after all slide markdown
- show up in the speaker notes
- uses markdown 


---
@title[gitpitch Widget]
### <p align="center"<span class="gold"   >Gitpitch Widget </span></p>
<span style="font-size:0.7em">
GitPitch provides a number of unique syntax shortcuts supported by <b>PITCHME.md</b> markdown that can be used to generate rich visual components - aka. widgets - on any slide.
See <a href="https://gitpitch.com/docs/markdown-features/widgets/"> link</a>
</span>


- &commat;box - Render Boxed Text
- &commat;quote - Render Styled Quotes
- &commat;fa - Render Font-Awesome Icons <a href='https://fontawesome.com/cheatsheet'>Link</a>
- &commat;img - Render Styled Images
- &commat;snap - Render Content using Snap Layouts
- &commat;size, &commat;color, &commat;css, &commat;title, &commat;transition - for shortcut markdown syntax

Note:



---  
@title[Lesson Objective]
<BR>
### <p align="center"<span class="gold"   >Lesson Objective </span></p>

<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
<span style="font-size:0.9em"><font color="#A8ff60"><i>Example of a list of objectives for this training presentation</i></font></span>

<ul style="list-style-type:none">
 <li>@fa[certificate gp-bullet-green]<span style="font-size:0.9em">&nbsp;&nbsp;This item falls across 2 lines<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Second line of this item</span> </li>
 <li>@fa[certificate gp-bullet-cyan]<span style="font-size:0.9em">&nbsp;&nbsp;Item 2</span></li>
 <li>@fa[certificate gp-bullet-gold]<span style="font-size:0.9em">&nbsp;&nbsp;Item 3</span> </li>
 <li>@fa[certificate gp-bullet-ltgreen]<span style="font-size:0.9em">&nbsp;&nbsp;Item 4</span></li>
 <li>@fa[certificate gp-bullet-yellow]<span style="font-size:0.9em">&nbsp;&nbsp;Item 5</span> </li>
 <li>@fa[certificate gp-bullet-magenta]<span style="font-size:0.9em">&nbsp;&nbsp;Item 6</span> </li>
</ul>

---?image=assets/images/binary-strings-black2.jpg
@title[Overview Section break]
<br><br><br><br><br><br><br>
### <span class="gold"  >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Example Section Break </span>
<span style="font-size:0.9em" >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Details about this section</span>

Note:

## using the "Note:" tag keyword
- must be after all slide markdown
- show up in the speaker notes
- uses markdown 

---  
@title[FA Fragment bullets]
<br>
<p align="center"<span class="gold"   ><b>Example using Font Awesome bullets in a Build slide</b></span></p>
<br>
@ul[no-bullet]
 - @fa[star gp-bullet-magenta]<span style="font-size:0.9em">&nbsp;&nbsp;First item crosses 2 lines<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; next line for item 1</span> 
 - @fa[star gp-bullet-gold]<span style="font-size:0.9em">&nbsp;&nbsp;Item 2</span> 
 - @fa[star gp-bullet-green]<span style="font-size:0.9em">&nbsp;&nbsp;Item 3</span> 
 - @fa[star gp-bullet-cyan]<span style="font-size:0.9em">&nbsp;&nbsp;Item 4</span>
 - @fa[star gp-bullet-ltgreen]<span style="font-size:0.9em">&nbsp;&nbsp;Item 5</span>
@ulend


---
@title[example Boxes Fragments]
#### <p align="right"><span class="gold" >Example Boxes</span></p>
<span style="font-size:0.9em"><font color="#A8ff60"><i>Example using Boxes in a build slide</i></font></span>


@snap[north-west span-35 fragment]
@css[text-yellow](<br><br>&nbsp; <br>&nbsp;)
@box[bg-lt-blue-pp text-white  waved  ](<b>Item 1:</b> Item 1 more detail<br>&nbsp;)
@snapend

@snap[north span-35 fragment]
@css[text-yellow](<br> <br>&nbsp;<br>&nbsp;)
@box[bg-royal text-white waved ](<b>Item 2</b><br><br>&nbsp;)
@snapend

@snap[north-east span-35 fragment]
@css[text-yellow](<br><br>&nbsp; <br>&nbsp;)
@box[bg-green-pp text-white waved ](<b>Item 3</b><br><br>&nbsp;)
@snapend

@snap[south-west span-35 fragment]
@box[bg-yellow text-blue  waved ](<b>Item 4 with more details next line</b><br>&nbsp;)
@css[text-yellow]( <br>&nbsp;)
@snapend

@snap[south span-35 fragment]
@box[bg-brick text-white waved ](<b>Item 5 with details and more</b><br><br>)
@css[text-yellow]( <br>&nbsp;)
@snapend

@snap[south-east span-35 fragment]
@box[bg-purple-pp text-white waved ](<b>Item 6 with details as well</b><br>&nbsp;)
@css[text-yellow]( <br>&nbsp;)
@snapend


 
Note:


---?image=/assets/images/slides/Slide71.JPG
@title[Key Points for More Secure Software MMI Handlers]
<span style="font-size:0.9em"><font color="#A8ff60"><i>Example using slide with image for entire slide but only right side</i></font></span>

<p align="right"><span class="gold" ><b>Title Topic with Image for this side</b></span></p>
<br>
<div class="left1">
     <ul>
        <li><span style="font-size:0.8em" >Item point 1  </span></li>
        <li><span style="font-size:0.8em" >Item point 2  </span></li>
        <li><span style="font-size:0.8em" >Item point 3   </span></li>
        <li><span style="font-size:0.8em" >Item point 4 </span></li>
        <li><span style="font-size:0.8em" >Item point 5  </span></li>
      </ul>
</div>
<div class="right1">
   <span style="font-size:01.5em" ><font color="yellow"><b>      </b></font></span>
</div>


---
@title[Example: Image build]
<p align="center"><span style="font-size:01.1em"><font color="#e49436"><b>Shell Scripts (Benefits)</b></font></span></p>
<p align="right"><span style="font-size:0.9em"><font color="#A8ff60"><i>Example images as a build slide</i></font></span></p>

@snap[north-west span-25  ]
<br>
<br>
![shell1](/assets/images/shell1.png)
@snapend

@snap[north-east span-70   ]
<br>
<br>
<br>
<br>
<span style="font-size:01.2em">Example 1 about this topic &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
@snapend


@snap[east span-25 fragment ]
![shell2](/assets/images/shell2.png)
@snapend

@snap[west span-70 fragment  ]
<span style="font-size:01.2em">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Example 2 about this  topic&nbsp;&nbsp;&nbsp;</span>
@snapend


@snap[south-west span-25 fragment ]
![shell3](/assets/images/shell3.png)
@snapend

@snap[south-east span-70 fragment  ]
<span style="font-size:01.2em">Example 3 about this topic</span>
<br>
<br>
<br>
@snapend


@snap[south span-100 ]
<span style="font-size:0.5em">@color[#A8ff60](<i>NOTE the alignment of text on this slide</i>)</span>
@snapend
Note: 



---
@title[Colors 01]
<p style="line-height:60%"  align="center" ><span class="gold"   >Colors </span><br>
<span style="font-size:0.6em">Some example colors for boxes and text defined in `patchme.css`</span></p>

@snap[north-west span-25 ]
<br>
<br>
<span style="font-size:0.9em">Reds -purples</span>
@box[bg-magenta text-white rounded my-box-pad2  ](<p style="line-height:60%">magenta <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-pink text-white rounded my-box-pad2  ](<p style="line-height:60%">pink <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-red-pp text-white rounded my-box-pad2  ](<p style="line-height:60%">red-pp <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-purple text-white rounded my-box-pad2  ](<p style="line-height:60%">purple <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-purple-pp text-white rounded my-box-pad2  ](<p style="line-height:60%">purple-pp <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@snapend



@snap[north span-25 ]
<br>
<br>
<span style="font-size:0.9em">Oranges</span>
@box[bg-brick text-white rounded my-box-pad2  ](<p style="line-height:60%">brick <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-orange text-white rounded my-box-pad2  ](<p style="line-height:60%">orange <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-lt-orange text-white rounded my-box-pad2  ](<p style="line-height:60%">lt-orange <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-gold2 text-white rounded my-box-pad2  ](<p style="line-height:60%">gold2 <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-lt-gold text-white rounded my-box-pad2  ](<p style="line-height:60%">lt-gold <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@snapend


@snap[north-east span-25 ]
<br>
<br>
<span style="font-size:0.9em">yellows</span>
@box[bg-yellow-pp text-black rounded my-box-pad2  ](<p style="line-height:60%">yellow-pp <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-yellow text-black rounded my-box-pad2  ](<p style="line-height:60%">yellow <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-cream text-black rounded my-box-pad2  ](<p style="line-height:60%">cream <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-cream2 text-black rounded my-box-pad2  ](<p style="line-height:60%">cream2 <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-white text-black rounded my-box-pad2  ](<p style="line-height:60%">white <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@snapend


@snap[south span-100 ]
<span style="font-size:0.5em">@color[#A8ff60](<i>NOTE the next slide with "&or;" are subsets using "&plus;&plus;&plus;" delimiter  </i>)</span>
@snapend

+++
@title[Colors 02]
<p style="line-height:60%"  align="center" ><span class="gold"   >Colors </span> - <span style="font-size:0.6em">Continued</span></p>

@snap[north-west span-25 ]
<br>
<br>
<span style="font-size:0.9em">blues</span>
@box[bg-light-lt-blue-pp text-white rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.8em">light-lt-blue-pp <br>&nbsp;</span></p>)
@box[bg-lt-blue-pp text-white rounded my-box-pad2  ](<p style="line-height:60%">lt-blue-pp <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-blue text-white rounded my-box-pad2  ](<p style="line-height:60%">blue <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-blue-pp text-white rounded my-box-pad2  ](<p style="line-height:60%">blue-pp <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-royal text-white rounded my-box-pad2  ](<p style="line-height:60%">royal <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@snapend



@snap[north span-25 ]
<br>
<br>
<span style="font-size:0.9em">blues - greens</span>
@box[bg-navy text-white rounded my-box-pad2  ](<p style="line-height:60%">navy <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-cyan text-white rounded my-box-pad2  ](<p style="line-height:60%">cyan <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-green text-white rounded my-box-pad2  ](<p style="line-height:60%">green <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-green-pp text-white rounded my-box-pad2  ](<p style="line-height:60%">green-pp <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-green2 text-white rounded my-box-pad2  ](<p style="line-height:60%">green2 <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@snapend


@snap[north-east span-25 ]
<br>
<br>
<span style="font-size:0.9em">other colors</span>
@box[bg-u-term text-white rounded my-box-pad2  ](<p style="line-height:60%">u-term <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-ubuntu text-white rounded my-box-pad2  ](<p style="line-height:60%">ubuntu <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@box[bg-black text-white rounded my-box-pad2  ](<p style="line-height:60%">black <span style="font-size:0.9em"><br>&nbsp;</span></p>)
@snapend


+++
@title[Colors 03]
<p style="line-height:60%"  align="center" ><span class="gold"   >Colors </span> - <span style="font-size:0.6em">Greys - Grays</span></p>

@snap[north-west span-25 ]
<br>
<br>
<span style="font-size:0.9em">Dark Grey</span>
@box[bg-grey-00 text-white rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.8em">grey-00 <br>&nbsp;</span></p>)
@box[bg-grey-05 text-white rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.9em">grey-05<br>&nbsp;</span></p>)
@box[bg-grey-15 text-white rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.9em">grey-15<br>&nbsp;</span></p>)
@box[bg-grey-25 text-white rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.9em">grey-25<br>&nbsp;</span></p>)
@box[bg-grey-35 text-white rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.9em">grey-35<br>&nbsp;</span></p>)
@snapend


@snap[north span-25 ]
<br>
<br>
<span style="font-size:0.9em">Light Grey</span>
@box[bg-grey-50 text-black rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.8em">grey-50 <br>&nbsp;</span></p>)
@box[bg-grey-65 text-black rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.9em">grey-65<br>&nbsp;</span></p>)
@box[bg-grey-75 text-black rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.9em">grey-75<br>&nbsp;</span></p>)
@box[bg-grey-85 text-black rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.9em">grey-85<br>&nbsp;</span></p>)
@box[bg-grey-90 text-black rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.9em">grey-90<br>&nbsp;</span></p>)
@snapend


@snap[north-east span-25 ]
<br>
<br>
<span style="font-size:0.9em">white/black</span>
@box[bg-black text-white rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.8em">black grey-00<br>&nbsp;</span></p>)
@box[bg-white text-black rounded my-box-pad2  ](<p style="line-height:60%"><span style="font-size:0.9em">white grey-100<br>&nbsp;</span></p>)
@snapend
---
@title[Colors - text]
<p style="line-height:60%"  align="center" ><span class="gold"   >Colors </span><br>
<span style="font-size:0.6em">Some example colors for  text defined in `patchme.css`</span></p>
<p style="line-height:80%" ><span style="font-size:0.85em">
@color[ yellow]( example color: yellow)<br>
@color[#00FFFF]( example color: cyan)<br>
@color[#87E2A9 ]( example color: lt_green )<br>
@color[#A8ff60 ]( example color: lt_green2)<br>
@color[#FFC000 ]( example color: gold2 )<br>
@color[#BF5122 ]( example color: brick - hyper link )<br>
@color[#e49436 ]( example color: gold - Slide Titles)<br>
@color[gray ]( example color: gray)<br>
@color[black ]( example color: black)<br>
@color[#A20000]( example color: red)<br>
@color[#ffffff]( white - default)
</span></p>



Note:

---  
@title[Summary]
<BR>
### <p align="center"<span class="gold"   >Summary </span></p>

<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
<span style="font-size:0.9em"><font color="#A8ff60"><i>Summary should match list of objectives</i></font></span>

<ul style="list-style-type:none">
 <li>@fa[certificate gp-bullet-green]<span style="font-size:0.9em">&nbsp;&nbsp;This item falls across 2 lines<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Second line of this item</span> </li>
 <li>@fa[certificate gp-bullet-cyan]<span style="font-size:0.9em">&nbsp;&nbsp;Item 2</span></li>
 <li>@fa[certificate gp-bullet-gold]<span style="font-size:0.9em">&nbsp;&nbsp;Item 3</span> </li>
 <li>@fa[certificate gp-bullet-ltgreen]<span style="font-size:0.9em">&nbsp;&nbsp;Item 4</span></li>
 <li>@fa[certificate gp-bullet-yellow]<span style="font-size:0.9em">&nbsp;&nbsp;Item 5</span> </li>
 <li>@fa[certificate gp-bullet-magenta]<span style="font-size:0.9em">&nbsp;&nbsp;Item 6</span> </li>
</ul>


---?image=assets/images/gitpitch-audience.jpg
@title[Questions]
<br>
![Questions](/assets/images/questions.JPG =10x) 

---
@title[return to main]
#### <p align="center"<span class="gold"   >Return to Main </span></p>
@snap[north span-20 ]
<br>
<br>
<br>
<br>
<a href="https://github.com/tianocore-training/Tianocore_Training_Contents/wiki">
![trainingLogo](/assets/images/returnTrainingLogo.png)</a>
@snapend

<br>
<br>
<br>
<br>
<span style="font-size:0.9em">&nbsp;&nbsp;Return to Training Table of contents <a href="https://github.com/tianocore-training/Tianocore_Training_Contents/wiki">link</a></span>




---?image=assets/images/gitpitch-audience.jpg
@title[Logo Slide]
<br><br><br>
![Logo Slide](/assets/images/TianocoreLogo.png =10x)



---
@title[Acknowledgements]
#### <p align="center"><span class="gold"   >Acknowledgements</span></p>

```c++
/**
Redistribution and use in source (original document form) and 'compiled' forms (converted
to PDF, epub, HTML and other formats) with or without modification, are permitted provided
that the following conditions are met:

Redistributions of source code (original document form) must retain the above copyright 
notice, this list of conditions and the following disclaimer as the first lines of this 
file unmodified.

Redistributions in compiled form (transformed to other DTDs, converted to PDF, epub, HTML
and other formats) must reproduce the above copyright notice, this list of conditions and 
the following disclaimer in the documentation and/or other materials provided with the 
distribution.

THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR IMPLIED 
WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND 
FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL TIANOCORE PROJECT BE 
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES 
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, 
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, 
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) 
ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF ADVISED OF THE POSSIBILITY 
OF SUCH DAMAGE.

Copyright (c) 2019, Intel Corporation. All rights reserved.
**/

```

---
@title[Backup]
<BR>
<BR>
<BR>

##### Backup


---
@title[GitPitch]
<p align="center"<span class="gold"   ><b>About GitPitch</b></span></p>
<p style="line-height:70%">The Markdown Presentation Service on Git <span style="font-size:0.7em">see documentation at: https://gitpitch.com/docs/ </span></p>
<span style="font-size:0.9em">GitPitch Key press controls:</span>
<ul style="line-height:0.8;">
 <li><span style="font-size:0.7em">Press<font color="yellow"> **F** </font>for full screen</span></li>
 <li><span style="font-size:0.7em">Press<font color="yellow"> **O** </font>for Overview</span></li>
 <li><span style="font-size:0.7em">Press<font color="yellow"> **B** </font>for Blackout </span></li>
 <li><span style="font-size:0.7em">Press<font color="yellow"> **M** </font>for menu</span></li>
 <li><span style="font-size:0.7em">Press<font color="yellow"> **?** </font>for help</span></li>
 <li><span style="font-size:0.7em">Press<font color="yellow"> **S** </font>for Speaker notes</span></li>
 <li><span style="font-size:0.7em">To get a <font color="yellow"> PDF </font>of the presentation, use the lower left white bars ( "&equiv;" ) and select "Print Version(.pdf)"</span></li>
 <li><span style="font-size:0.7em"><font color="yellow">Navigation</font>  Space - Arrow keys - Page Down ( Arrows at bottom right show Next slide or sub-slides) ( " < &or; > ") see <a href="https://gitpitch.com/docs/foundation-features/keyboard-controls/"> full list</a> </span></li>
</ul> 
 
