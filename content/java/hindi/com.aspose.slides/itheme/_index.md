---
title: ITheme
second_title: Aspose.Slides जावा API संदर्भ
description: एक थीम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/itheme/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

एक थीम का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | रंग योजना लौटाता है। |
| [getFontScheme()](#getFontScheme--) | फ़ॉन्ट योजना लौटाता है। |
| [getFormatScheme()](#getFormatScheme--) | आकार फ़ॉर्मेट योजना लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी थीम डेटा प्राप्त करता है। |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


रंग योजना लौटाता है। केवल-पठन [IColorScheme](../../com.aspose.slides/icolorscheme)।

**वापसी:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


फ़ॉन्ट योजना लौटाता है। केवल-पठन [IFontScheme](../../com.aspose.slides/ifontscheme)।

**वापसी:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


आकार फ़ॉर्मेट योजना लौटाता है। केवल-पठन [IFormatScheme](../../com.aspose.slides/iformatscheme)।

**वापसी:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


विरासत लागू करके प्रभावी थीम डेटा प्राप्त करता है।

**वापसी:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - एक [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).