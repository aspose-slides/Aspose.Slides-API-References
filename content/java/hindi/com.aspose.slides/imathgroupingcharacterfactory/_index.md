---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math grouping character
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
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | गणित समूह वर्ण बनाता है |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | गणित समूह वर्ण बनाता है |
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
| verticalJustification | int | ऊर्ध्वाधर संरेखण |

**रिटर्न:**
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

**रिटर्न:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - नया समूह वर्ण तत्व