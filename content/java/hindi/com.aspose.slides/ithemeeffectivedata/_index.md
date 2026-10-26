---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /hi/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

अपरिवर्तनीय वस्तु जो प्रभावी थीम गुणों को सम्मिलित करती है।

--------------------

यह इंटरफ़ेस [ITheme](../../com.aspose.slides/itheme) इंटरफ़ेस के साथ उपयोग किया जाता है ताकि विरासत लागू होकर प्रभावी फ़ॉर्मेटिंग मान वापस किया जा सके।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | रंग योजना को लौटाता है। |
| [getFontScheme()](#getFontScheme--) | फ़ॉन्ट योजना को लौटाता है। |
| [getFormatScheme()](#getFormatScheme--) | आकार स्वरूप योजना को लौटाता है। |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```


रंग योजना को लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**वापसी:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - रंग योजना [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


फ़ॉन्ट योजना को लौटाता है। केवल-रीड [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)।

**वापसी:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


आकार स्वरूप योजना को लौटाता है। केवल-रीड [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)।

**वापसी:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)