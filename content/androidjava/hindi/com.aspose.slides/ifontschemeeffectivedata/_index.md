---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: निष्क्रिय ऑब्जेक्ट जिसमें प्रभावी फ़ॉन्ट स्कीम गुण होते हैं।
type: docs
url: /hi/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

निष्क्रिय ऑब्जेक्ट जिसमें प्रभावी फ़ॉन्ट स्कीम गुण होते हैं।

--------------------

यह इंटरफ़ेस [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) का एक भाग के रूप में उपयोग किया जाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getMinor()](#getMinor--) | स्लाइड के "body" भाग के लिए फ़ॉन्ट संग्रह लौटाता है। |
| [getMajor()](#getMajor--) | स्लाइड के "heading" भाग के लिए फ़ॉन्ट संग्रह लौटाता है। |
| [getName()](#getName--) | फ़ॉन्ट स्कीम का नाम लौटाता है। |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


स्लाइड के "body" भाग के लिए फ़ॉन्ट संग्रह लौटाता है। केवल-पढ़ने योग्य [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)।

**वापसी:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


स्लाइड के "heading" भाग के लिए फ़ॉन्ट संग्रह लौटाता है। केवल-पढ़ने योग्य [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)।

**वापसी:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


फ़ॉन्ट स्कीम नाम लौटाता है। केवल-पढ़ने योग्य String।

**वापसी:**
java.lang.String