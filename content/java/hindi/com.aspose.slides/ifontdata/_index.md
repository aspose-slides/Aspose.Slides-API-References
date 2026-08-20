---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: एक फ़ॉन्ट परिभाषा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

एक फ़ॉन्ट परिभाषा का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getFontName()](#getFontName--) | फ़ॉन्ट नाम लौटाता है। |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | फ़ॉन्ट नाम लौटाता है, थीम संदर्भ को उपयोग किए गए वास्तविक फ़ॉन्ट से बदलते हुए। |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

फ़ॉन्ट नाम लौटाता है। केवल-पढ़ने योग्य String.

**रिटर्न:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

फ़ॉन्ट नाम लौटाता है, थीम संदर्भ को उपयोग किए गए वास्तविक फ़ॉन्ट से बदलते हुए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Theme जिससे थीम वाला फ़ॉन्ट नाम लिया जाना चाहिए। कॉलर की जिम्मेदारी है कि सही मान प्रदान करे। |

**रिटर्न:**
java.lang.String - फ़ॉन्ट नाम।