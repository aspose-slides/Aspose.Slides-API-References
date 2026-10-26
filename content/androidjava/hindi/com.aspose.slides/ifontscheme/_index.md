---
title: IFontScheme
second_title: Aspose.Slides for Android via Java API Reference
description: थीम-परिभाषित फ़ॉन्ट्स को संग्रहीत करता है।
type: docs
url: /hi/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

थीम-परिभाषित फ़ॉन्ट्स को संग्रहीत करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getMinor()](#getMinor--) | स्लाइड के "body" भाग के लिए फ़ॉन्ट्स संग्रह लौटाता है। |
| [getMajor()](#getMajor--) | स्लाइड के "heading" भाग के लिए फ़ॉन्ट्स संग्रह लौटाता है। |
| [getName()](#getName--) | फ़ॉन्ट स्कीम का नाम लौटाता है। |
| [setName(String value)](#setName-java.lang.String-) | फ़ॉन्ट स्कीम का नाम लौटाता है। |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```

स्लाइड के "body" भाग के लिए फ़ॉन्ट्स संग्रह लौटाता है। केवल-पढ़ने योग्य [IFonts](../../com.aspose.slides/ifonts)।

**रिटर्न:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```

स्लाइड के "heading" भाग के लिए फ़ॉन्ट्स संग्रह लौटाता है। केवल-पढ़ने योग्य [IFonts](../../com.aspose.slides/ifonts)।

**रिटर्न:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```

फ़ॉन्ट स्कीम का नाम लौटाता है। पढ़ने/लेने योग्य String.

**रिटर्न:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

फ़ॉन्ट स्कीम का नाम लौटाता है। पढ़ने/लेने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |