---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: फ़ॉन्ट्स संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ifonts/
---```
public interface IFonts
```

फ़ॉन्ट्स संग्रह का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Latin फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [getEastAsianFont()](#getEastAsianFont--) | East Asian फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | East Asian फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [getComplexScriptFont()](#getComplexScriptFont--) | complex script फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | complex script फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [getScriptFontMap()](#getScriptFontMap--) | प्रस्तुति में सभी स्क्रिप्ट फ़ॉन्ट परिभाषाओं का शब्दकोश लौटाता है। |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | प्रस्तुति थीम से एक विशिष्ट स्क्रिप्ट टैग से संबंधित फ़ॉन्ट नाम प्राप्त करता है। |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | एक विशिष्ट स्क्रिप्ट टैग को फ़ॉन्ट नाम असाइन करता है, जिससे प्रस्तुति में उस स्क्रिप्ट का टेक्स्ट कैसे रेंडर होगा निर्धारित होता है। |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | थीम के फ़ॉन्ट संग्रह से एक विशिष्ट स्क्रिप्ट टैग से संबंधित फ़ॉन्ट सेटिंग को हटाता है। |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Latin फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Latin फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

East Asian फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

East Asian फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

complex script फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

complex script फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

प्रस्तुति में सभी स्क्रिप्ट फ़ॉन्ट परिभाषाओं का शब्दकोश लौटाता है।

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**रिटर्न:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - स्क्रिप्ट कोड को फ़ॉन्ट नामों से मैप करने वाला शब्दकोश।

### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

प्रस्तुति थीम से एक विशिष्ट स्क्रिप्ट टैग से संबंधित फ़ॉन्ट नाम प्राप्त करता है।

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| script | java.lang.String | वह BCP-47 स्क्रिप्ट कोड (जैसे "Latn", "Cyrl", "Jpan") जो लेखन प्रणाली की पहचान करता है। |

**रिटर्न:**
java.lang.String - निर्दिष्ट स्क्रिप्ट के लिए उपयोग किया जाने वाला फ़ॉन्ट नाम, या null यदि स्क्रिप्ट परिभाषित नहीं है।

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

एक विशिष्ट स्क्रिप्ट टैग को फ़ॉन्ट नाम असाइन करता है, जिससे प्रस्तुति में उस स्क्रिप्ट का टेक्स्ट कैसे रेंडर होगा निर्धारित होता है।

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| script | java.lang.String | BCP-47 स्क्रिप्ट कोड (जैसे "Arab", "Hebr", "Hans") जो लेखन प्रणाली की पहचान करता है। |
| fontName | java.lang.String | निर्दिष्ट स्क्रिप्ट के लिए असाइन किया जाने वाला फ़ॉन्ट नाम। |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

थीम के फ़ॉन्ट संग्रह से एक विशिष्ट स्क्रिप्ट टैग से संबंधित फ़ॉन्ट सेटिंग को हटाता है।

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| script | java.lang.String | वह BCP-47 स्क्रिप्ट कोड जिसका फ़ॉन्ट सेटिंग हटाया जाना चाहिए। |