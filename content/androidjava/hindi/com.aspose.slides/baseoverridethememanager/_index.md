---
title: BaseOverrideThemeManager
second_title: Android के लिए Aspose.Slides – Java API रेफ़रेंस
description: विभिन्न प्रकार के ओवरराइडेड थीम तक पहुँच प्रदान करने वाली कक्षाओं के लिए बेस क्लास।
type: docs
url: /hi/com.aspose.slides/baseoverridethememanager/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

विभिन्न प्रकार के ओवरराइडेड थीम तक पहुंच प्रदान करने वाली कक्षाओं के लिए बेस क्लास।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | ओवरराइडिंग थीम ऑब्जेक्ट को लौटाता है। |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | ओवरराइडिंग थीम ऑब्जेक्ट को लौटाता है। |
| [createThemeEffective()](#createThemeEffective--) | थीम ऑब्जेक्ट को लौटाता है। |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | निर्धारित करता है कि OverrideTheme विरासत में मिली प्रभावी थीम को ओवरराइड करता है या नहीं। |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | स्लाइड पर अतिरिक्त रंग योजना लागू करता है। |

### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

ओवरराइडिंग थीम ऑब्जेक्ट को लौटाता है। पढ़ें/लिखें [IOverrideTheme](../../com.aspose.slides/ioverridetheme)।

**वापसी:**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)

### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

ओवरराइडिंग थीम ऑब्जेक्ट को लौटाता है। पढ़ें/लिखें [IOverrideTheme](../../com.aspose.slides/ioverridetheme)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

थीम ऑब्जेक्ट को लौटाता है।

**वापसी:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

निर्धारित करता है कि OverrideTheme विरासत में मिली प्रभावी थीम को ओवरराइड करता है या नहीं। OverrideTheme को ओवरराइड करने के लिए OverrideTheme.Init*() मेथड्स का उपयोग करें। OverrideTheme को ओवरराइड करने से रोकने के लिए OverrideTheme.Clear() मेथड का उपयोग करें। केवल पढ़ने योग्य बूलियन।

**वापसी:**  
boolean

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

स्लाइड पर अतिरिक्त रंग योजना लागू करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) ऑब्जेक्ट। |