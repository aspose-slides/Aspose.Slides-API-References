---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: फ़ॉन्ट परिभाषा दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

फ़ॉन्ट परिभाषा दर्शाता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getFontName()](#getFontName--) | फ़ॉन्ट नाम लौटाता है। |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | फ़ॉन्ट नाम लौटाता है, थीम संदर्भ को वास्तविक उपयोग किए गए फ़ॉन्ट से बदलते हुए। |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

फ़ॉन्ट नाम लौटाता है। केवल-पढ़ने योग्य String.

**वापसी:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

फ़ॉन्ट नाम लौटाता है, थीम संदर्भ को वास्तविक उपयोग किए गए फ़ॉन्ट से बदलते हुए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | थीम जिससे थीम्ड फ़ॉन्ट नाम लेना चाहिए। यह कॉलर की जिम्मेदारी है कि वह सही मान प्रदान करे। |

**वापसी:**
java.lang.String - फ़ॉन्ट नाम।