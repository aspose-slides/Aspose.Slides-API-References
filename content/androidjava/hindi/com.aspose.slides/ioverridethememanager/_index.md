---
title: IOverrideThemeManager
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: विभिन्न प्रकार के ओवरराइडेड थीम्स तक पहुंच प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/ioverridethememanager/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

विभिन्न प्रकार के ओवरराइडेड थीम्स तक पहुंच प्रदान करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | निर्धारित करता है कि OverrideTheme विरासत में मिली प्रभावी थीम को ओवरराइड करता है या नहीं। |
| [getOverrideTheme()](#getOverrideTheme--) | ओवरराइडिंग थीम ऑब्जेक्ट वापस करता है। |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | ओवरराइडिंग थीम ऑब्जेक्ट वापस करता है। |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


निर्धारित करता है कि OverrideTheme विरासत में मिली प्रभावी थीम को ओवरराइड करता है या नहीं। ओवरराइडिंग के लिए OverrideTheme को सक्षम करने हेतु OverrideTheme.Init\*() मेथड्स का उपयोग करें। ओवरराइडिंग से OverrideTheme को अक्षम करने हेतु OverrideTheme.Clear() मेथड का उपयोग करें। केवल-पढ़ने योग्य बूलियन।

**Returns:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


ओवरराइडिंग थीम ऑब्जेक्ट वापस करता है। पढ़ने/लिखने योग्य [IOverrideTheme](../../com.aspose.slides/ioverridetheme)।

**Returns:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


ओवरराइडिंग थीम ऑब्जेक्ट वापस करता है। पढ़ने/लिखने योग्य [IOverrideTheme](../../com.aspose.slides/ioverridetheme)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |