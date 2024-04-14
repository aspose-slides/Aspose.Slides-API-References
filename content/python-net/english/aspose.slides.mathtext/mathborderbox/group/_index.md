---
title: group method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathborderbox/group/
weight: 80
---


## group {#}
Places this element in a group using a bottom curly bracket

### Returns

New instance of type [`IMathGroupingCharacter`](/slides/python-net/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```




## group {#char-mathtopbotpositions-mathtopbotpositions}
Places this element in a group using a grouping character such as bottom curly bracket or another

### Returns

New instance of type [`IMathGroupingCharacter`](/slides/python-net/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| character | char | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | MathTopBotPositions | Position of grouping character |
| vertical_justification | MathTopBotPositions | Vertical justification of group character.<br/><br/>            Specifies the alignment of the object with respect to the baseline.<br/><br/>            For example, when the group character is above the object, <br/><br/>            VerticalJustification of Top signifies that the top of the object falls on the baseline;<br/><br/>            when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |



