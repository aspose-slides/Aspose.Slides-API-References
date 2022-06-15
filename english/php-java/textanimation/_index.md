---
title: TextAnimation
type: docs
weight: 0
url: /php-java/textanimation/
---

# TextAnimation class

 Represent text animation.
 

## Constructors

| name | description |
| --- | --- |
| [TextAnimation](/slides/php-java/textanimation/textanimation/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [addEffect](/slides/php-java/textanimation/addeffect/)(int, int, int) | IEffect | Add new effect to the end of current sequence to end of group text animations. Only valid if count of text paragraphs equal or greater of counts effect of this group! |
| [getBuildType](/slides/php-java/textanimation/getbuildtype/)() | int | List of build type (for exp. Paragraph 1,2,3, All at Once) of text animation. Read/write BuildType. |
| [getEffectAnimateBackgroundShape](/slides/php-java/textanimation/geteffectanimatebackgroundshape/)() | IEffect | Linked shape effect with group or not (null). Read/write IEffect. |
| [setBuildType](/slides/php-java/textanimation/setbuildtype/)(int) | void | List of build type (for exp. Paragraph 1,2,3, All at Once) of text animation. Read/write BuildType. |
| [setEffectAnimateBackgroundShape](/slides/php-java/textanimation/seteffectanimatebackgroundshape/)(IEffect) | void | Linked shape effect with group or not (null). Read/write IEffect. |
