---
title: TextAnimation
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/textanimation/
---

## TextAnimation class

 Represent text animation.
 
###TextAnimation{#TextAnimation}

| Name | Description |
| --- | --- |
| TextAnimation() |  |

 **Result**
TextAnimation


---


###addEffect{#addEffect}

| Name | Description |
| --- | --- |
| addEffect (int, int, int) | Add new effect to the end of current sequence to end of group text animations. Only valid if count of text paragraphs equal or greater of counts effect of this group! |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| effectType | int | Type of an animation effect EffectType |
| subtype | int | Subtypes of animation effect EffectSubtype |
| triggerType | int | Trigger type of effect EffectTriggerType |

 **Result**
[Effect](../effect)


---


###getBuildType{#getBuildType}

| Name | Description |
| --- | --- |
| getBuildType () | List of build type (for exp. Paragraph 1,2,3, All at Once) of text animation. Read/write BuildType. |

 **Result**
int


---


###getEffectAnimateBackgroundShape{#getEffectAnimateBackgroundShape}

| Name | Description |
| --- | --- |
| getEffectAnimateBackgroundShape () | Linked shape effect with group or not (null). Read/write IEffect. |

 **Result**
[Effect](../effect)


---


###setBuildType{#setBuildType}

| Name | Description |
| --- | --- |
| setBuildType (int) | List of build type (for exp. Paragraph 1,2,3, All at Once) of text animation. Read/write BuildType. |


---


###setEffectAnimateBackgroundShape{#setEffectAnimateBackgroundShape}

| Name | Description |
| --- | --- |
| setEffectAnimateBackgroundShape ([Effect](../effect)) | Linked shape effect with group or not (null). Read/write IEffect. |


---


