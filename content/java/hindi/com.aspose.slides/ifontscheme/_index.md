---
title: IFontScheme
second_title: Aspose.Slides for Java API संदर्भ
description: थीम-परिभाषित फ़ॉन्ट संग्रहीत करता है।
type: docs
url: /hi/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

थीम-परिभाषित फ़ॉन्ट संग्रहीत करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getMinor()](#getMinor--) | Returns the fonts collection for a "body" part of the slide. |
| [getMajor()](#getMajor--) | Returns the fonts collection for a "heading" part of the slide. |
| [getName()](#getName--) | Returns the font scheme name. |
| [setName(String value)](#setName-java.lang.String-) | Returns the font scheme name. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```

स्लाइड के "body" भाग के लिए फ़ॉन्ट संग्रह को लौटाता है। केवल-पढ़ने योग्य [IFonts](../../com.aspose.slides/ifonts).

**वापसी:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```

स्लाइड के "heading" भाग के लिए फ़ॉन्ट संग्रह को लौटाता है। केवल-पढ़ने योग्य [IFonts](../../com.aspose.slides/ifonts).

**वापसी:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```

फ़ॉन्ट स्कीम का नाम लौटाता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

फ़ॉन्ट स्कीम का नाम लौटाता है। पढ़ें/लिखें String.

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |