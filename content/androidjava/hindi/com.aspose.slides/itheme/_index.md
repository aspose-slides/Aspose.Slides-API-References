---
title: ITheme
second_title: Aspose.Slides for Android हेतु Java API संदर्भ
description: एक थीम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/itheme/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

एक थीम का प्रतिनिधित्व करता है।
## Methods

| Method | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | रंग योजना को लौटाता है। |
| [getFontScheme()](#getFontScheme--) | फ़ॉन्ट योजना को लौटाता है। |
| [getFormatScheme()](#getFormatScheme--) | शेप फ़ॉर्मेट योजना को लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी थीम डेटा प्राप्त करता है। |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


रंग योजना को लौटाता है। केवल पढ़ने योग्य [IColorScheme](../../com.aspose.slides/icolorscheme)।

**Returns:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


फ़ॉन्ट योजना को लौटाता है। केवल पढ़ने योग्य [IFontScheme](../../com.aspose.slides/ifontscheme)।

**Returns:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


शेप फ़ॉर्मेट योजना को लौटाता है। केवल पढ़ने योग्य [IFormatScheme](../../com.aspose.slides/iformatscheme)।

**Returns:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


विरासत लागू होने के साथ प्रभावी थीम डेटा प्राप्त करता है।

**Returns:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).