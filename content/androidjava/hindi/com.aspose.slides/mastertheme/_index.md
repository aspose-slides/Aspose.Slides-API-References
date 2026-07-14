---
title: MasterTheme
second_title: Aspose.Slides for Android, Java API रेफ़रेंस के माध्यम से
description: एक मास्टर थीम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/mastertheme/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

एक मुख्य थीम का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | रंग योजना को लौटाता है। |
| [getFontScheme()](#getFontScheme--) | फ़ॉन्ट योजना को लौटाता है। |
| [getFormatScheme()](#getFormatScheme--) | आकार प्रारूप योजना को लौटाता है। |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | अतिरिक्त रंग योजनाओं का संग्रह लौटाता है। |
| [getName()](#getName--) | एक थीम का नाम लौटाता है। |
| [setName(String value)](#setName-java.lang.String-) | एक थीम का नाम लौटाता है। |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```


रंग योजना को लौटाता है। केवल-पढ़ने योग्य [IColorScheme](../../com.aspose.slides/icolorscheme)।

**रिटर्न:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```


फ़ॉन्ट योजना को लौटाता है। केवल-पढ़ने योग्य [IFontScheme](../../com.aspose.slides/ifontscheme)।

**रिटर्न:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```


आकार प्रारूप योजना को लौटाता है। केवल-पढ़ने योग्य [IFormatScheme](../../com.aspose.slides/iformatscheme)।

**रिटर्न:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```


अतिरिक्त रंग योजनाओं का संग्रह लौटाता है। ये योजनाएँ प्रस्तुति की दिखावट को प्रभावित नहीं करतीं, उन्हें स्लाइड के लिए मुख्य रंग योजना के रूप में चुना जा सकता है। केवल-पढ़ने योग्य [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)।

**रिटर्न:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```


एक थीम का नाम लौटाता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


एक थीम का नाम लौटाता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल-पढ़ने योग्य long।

**रिटर्न:**
long