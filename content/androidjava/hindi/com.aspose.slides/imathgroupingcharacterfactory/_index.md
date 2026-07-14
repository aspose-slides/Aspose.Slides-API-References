---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: गणित समूह वर्ण बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

गणित समूह वर्ण बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


गणित समूह वर्ण बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | समूह वर्ण लागू करने के लिए गणित तत्व |
| character | char | समूह वर्ण |
| position | int | समूह वर्ण की स्थिति |
| verticalJustification | int | ऊर्ध्व दिशा संरेखण |

**रिटर्न मान:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - नया समूह वर्ण तत्व
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


गणित समूह वर्ण बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | समूह वर्ण लागू करने के लिए गणित तत्व |

**रिटर्न मान:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - नया समूह वर्ण तत्व