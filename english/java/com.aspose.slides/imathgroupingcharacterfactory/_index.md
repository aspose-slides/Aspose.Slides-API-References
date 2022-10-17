---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Reference
description:  Allows to create a math grouping character
type: docs
weight: 899
url: /java/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Allows to create a math grouping character

--------------------

For COM comparibility
## Methods

| Method | Description |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Creates a math grouping character

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply grouping character |
| character | char | grouping character |
| position | int | position of grouping character |
| verticalJustification | int | vertical justification |

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - new grouping character element
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Creates a math grouping character

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply grouping character |

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - new grouping character element
