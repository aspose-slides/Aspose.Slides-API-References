---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /hi/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

बाहरी फ़ॉन्टों के लिए फ़ाइल और मेमोरी स्रोत प्रदान करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | फ़ॉन्ट फ़ाइलों वाले फ़ोल्डर। |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | फ़ॉन्ट फ़ाइलों वाले फ़ोल्डर। |
| [getMemoryFonts()](#getMemoryFonts--) | बाइट ऐरे के रूप में प्रस्तुत फ़ॉन्ट्स का संग्रह। |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | बाइट ऐरे के रूप में प्रस्तुत फ़ॉन्ट्स का संग्रह। |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

फ़ॉन्ट फ़ाइलों वाले फ़ोल्डर। इन फ़ोल्डरों में स्थित सभी फ़ॉन्ट फ़ाइलें संग्रह में शामिल हैं। फ़ोल्डर जिन्हें पुनरावर्ती रूप से खोजा जाता है।

**रिटर्न:**  
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

फ़ॉन्ट फ़ाइलों वाले फ़ोल्डर। इन फ़ोल्डरों में स्थित सभी फ़ॉन्ट फ़ाइलें संग्रह में शामिल हैं। फ़ोल्डर जिन्हें पुनरावर्ती रूप से खोजा जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

बाइट ऐरे के रूप में प्रस्तुत फ़ॉन्ट्स का संग्रह।

**रिटर्न:**  
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

बाइट ऐरे के रूप में प्रस्तुत फ़ॉन्ट्स का संग्रह।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte[][] |  |