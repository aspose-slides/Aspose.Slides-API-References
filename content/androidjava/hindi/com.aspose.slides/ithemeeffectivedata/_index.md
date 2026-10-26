---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /hi/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

अपरिवर्तनीय वस्तु जिसमें प्रभावी थीम गुण होते हैं।

--------------------

यह इंटरफ़ेस [ITheme](../../com.aspose.slides/itheme) इंटरफ़ेस के साथ उपयोग किया जाता है ताकि विरासत लागू करके प्रभावी फॉर्मेटिंग मान लौटाए जा सकें।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | रंग योजना लौटाता है। |
| [getFontScheme()](#getFontScheme--) | फ़ॉन्ट योजना लौटाता है। |
| [getFormatScheme()](#getFormatScheme--) | आकार फ़ॉर्मेट योजना लौटाता है। |

### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```

रंग योजना लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| styleColor | java.lang.Integer | रंग java.lang.Integer |

**रिटर्न:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - रंग योजना [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)

### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

फ़ॉन्ट योजना लौटाता है। केवल पढ़ने योग्य [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)।

**रिटर्न:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)

### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

आकार फ़ॉर्मेट योजना लौटाता है। केवल पढ़ने योग्य [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)।

**रिटर्न:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)