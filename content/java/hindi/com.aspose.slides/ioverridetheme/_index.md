---
title: IOverrideTheme
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: एक अधिलेखित थीम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ioverridetheme/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

एक अधिलेखित थीम को दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isEmpty()](#isEmpty--) | सही मान का अर्थ है कि ColorScheme, FontScheme, FormatScheme null है और इस थीम ऑब्जेक्ट के साथ कोई भी अधिलेखित करना अक्षम किया गया है। |
| [initColorScheme()](#initColorScheme--) | InheritedTheme के ColorScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ ColorScheme को प्रारंभ करें। |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | InheritedTheme के ColorScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ ColorScheme को प्रारंभ करें। |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | InheritedTheme के ColorScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ ColorScheme को प्रारंभ करें। |
| [initFontScheme()](#initFontScheme--) | InheritedTheme के FontScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ FontScheme को प्रारंभ करें। |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | InheritedTheme के FontScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ FontScheme को प्रारंभ करें। |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | InheritedTheme के FontScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ FontScheme को प्रारंभ करें। |
| [initFormatScheme()](#initFormatScheme--) | InheritedTheme के FormatScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ FormatScheme को प्रारंभ करें। |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | InheritedTheme के FormatScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ FormatScheme को प्रारंभ करें। |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | InheritedTheme के FormatScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ FormatScheme को प्रारंभ करें। |
| [clear()](#clear--) | ColorScheme, FontScheme, FormatScheme को null सेट करें ताकि इस थीम ऑब्जेक्ट के साथ कोई भी अधिलेखित अक्षम हो जाए। |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

सही मान का अर्थ है कि ColorScheme, FontScheme, FormatScheme null है और इस थीम ऑब्जेक्ट के साथ कोई भी अधिलेखित करना अक्षम किया गया है। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

InheritedTheme के ColorScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ ColorScheme को प्रारंभ करें।

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

InheritedTheme के ColorScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ ColorScheme को प्रारंभ करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | आरंभ करने के लिए डेटा। |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

InheritedTheme के ColorScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ ColorScheme को प्रारंभ करें। और इस नए ऑब्जेक्ट का डेटा InheritedTheme के ColorScheme के डेटा से प्रारंभ करें।

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

InheritedTheme के FontScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ FontScheme को प्रारंभ करें।

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

InheritedTheme के FontScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ FontScheme को प्रारंभ करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | आरंभ करने के लिए डेटा। |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

InheritedTheme के FontScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ FontScheme को प्रारंभ करें। और इस नए ऑब्जेक्ट का डेटा InheritedTheme के FontScheme के डेटा से प्रारंभ करें।

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

InheritedTheme के FormatScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ FormatScheme को प्रारंभ करें।

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

InheritedTheme के FormatScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ FormatScheme को प्रारंभ करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | आरंभ करने के लिए डेटा। |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

InheritedTheme के FormatScheme को अधिलेखित करने के लिए नया ऑब्जेक्ट के साथ FormatScheme को प्रारंभ करें। और इस नए ऑब्जेक्ट का डेटा InheritedTheme के FormatScheme के डेटा से प्रारंभ करें।

### clear() {#clear--}
```
public abstract void clear()
```

ColorScheme, FontScheme, FormatScheme को null सेट करें ताकि इस थीम ऑब्जेक्ट के साथ कोई भी अधिलेखित अक्षम हो जाए।