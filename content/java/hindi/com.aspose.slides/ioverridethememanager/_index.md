---
title: IOverrideThemeManager
second_title: Aspose.Slides के लिए Java API संदर्भ
description: ओवरराइडेड थीम के विभिन्न प्रकारों तक पहुँच प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/ioverridethememanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

विभिन्न प्रकार के ओवरराइडेड थीम तक पहुँच प्रदान करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | निश्चित करता है कि OverrideTheme विरासत में मिले प्रभावी थीम को ओवरराइड करता है या नहीं। |
| [getOverrideTheme()](#getOverrideTheme--) | ओवरराइडिंग थीम ऑब्जेक्ट को लौटाता है। |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | ओवरराइडिंग थीम ऑब्जेक्ट को लौटाता है। |

### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

निश्चित करता है कि OverrideTheme विरासत में मिले प्रभावी थीम को ओवरराइड करता है या नहीं। ओवरराइडिंग को सक्षम करने के लिए OverrideTheme.Init*() विधियों का उपयोग करें। OverrideTheme को ओवरराइड करने से निष्क्रिय करने के लिए OverrideTheme.Clear() विधि का उपयोग करें। केवल पढ़ने योग्य बूलियन।

**रिटर्न:**
boolean

### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

ओवरराइडिंग थीम ऑब्जेक्ट को लौटाता है। पढ़ने/लिखने योग्य [IOverrideTheme](../../com.aspose.slides/ioverridetheme)।

**रिटर्न:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)

### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

ओवरराइडिंग थीम ऑब्जेक्ट को लौटाता है। पढ़ने/लिखने योग्य [IOverrideTheme](../../com.aspose.slides/ioverridetheme)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |