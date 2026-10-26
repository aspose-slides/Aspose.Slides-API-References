---
title: MasterTheme
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: एक मास्टर थीम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/mastertheme/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

एक मास्टर थीम का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | वर्णन |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | रंग योजना लौटाता है। |
| [getFontScheme()](#getFontScheme--) | फ़ॉन्ट योजना लौटाता है। |
| [getFormatScheme()](#getFormatScheme--) | आकृति फ़ॉर्मेट योजना लौटाता है। |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | अतिरिक्त रंग योजनाओं का संग्रह लौटाता है। |
| [getName()](#getName--) | एक थीम का नाम लौटाता है। |
| [setName(String value)](#setName-java.lang.String-) | एक थीम का नाम लौटाता है। |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```


रंग योजना लौटाता है। केवल-पढ़ने योग्य [IColorScheme](../../com.aspose.slides/icolorscheme).

**रिटर्न:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```


फ़ॉन्ट योजना लौटाता है। केवल-पढ़ने योग्य [IFontScheme](../../com.aspose.slides/ifontscheme).

**रिटर्न:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```


आकृति फ़ॉर्मेट योजना लौटाता है। केवल-पढ़ने योग्य [IFormatScheme](../../com.aspose.slides/iformatscheme).

**रिटर्न:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```


अतिरिक्त रंग योजनाओं का संग्रह लौटाता है। ये योजनाएँ प्रस्तुति के रूप को प्रभावित नहीं करतीं, इन्हें स्लाइड के लिए मुख्य रंग योजना के रूप में चुना जा सकता है। केवल-पढ़ने योग्य [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**रिटर्न:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```


एक थीम का नाम लौटाता है। पढ़ने/लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


एक थीम का नाम लौटाता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल-पढ़ने योग्य long.

**रिटर्न:**
long