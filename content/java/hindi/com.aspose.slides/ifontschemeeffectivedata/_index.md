---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: इम्यूटेबल ऑब्जेक्ट जिसमें प्रभावी फ़ॉन्ट स्कीम प्रॉपर्टीज़ शामिल हैं।
type: docs
url: /hi/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

इम्यूटेबल ऑब्जेक्ट जिसमें प्रभावी फ़ॉन्ट स्कीम प्रॉपर्टीज़ शामिल हैं।

--------------------

यह इंटरफ़ेस [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) का हिस्सा के रूप में उपयोग किया जाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getMinor()](#getMinor--) | स्लाइड के "body" भाग के लिए फ़ॉन्ट्स संग्रह लौटाता है। |
| [getMajor()](#getMajor--) | स्लाइड के "heading" भाग के लिए फ़ॉन्ट्स संग्रह लौटाता है। |
| [getName()](#getName--) | फ़ॉन्ट स्कीम का नाम लौटाता है। |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

स्लाइड के "body" भाग के लिए फ़ॉन्ट्स संग्रह लौटाता है। केवल-पढ़ने योग्य [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)।

**रिटर्न:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

स्लाइड के "heading" भाग के लिए फ़ॉन्ट्स संग्रह लौटाता है। केवल-पढ़ने योग्य [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)।

**रिटर्न:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

फ़ॉन्ट स्कीम का नाम लौटाता है। केवल-पढ़ने योग्य String।

**रिटर्न:**
java.lang.String