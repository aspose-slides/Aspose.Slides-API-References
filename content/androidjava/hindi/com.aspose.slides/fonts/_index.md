---
title: Fonts
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: फ़ॉन्ट संग्रह।
type: docs
url: /hi/com.aspose.slides/fonts/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

फ़ॉन्ट संग्रह।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | प्रस्तुति में सभी स्क्रिप्ट फ़ॉन्ट परिभाषाओं की शब्दकोश लौटाता है। |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | प्रस्तुति थीम से किसी विशिष्ट स्क्रिप्ट टैग से जुड़ा फ़ॉन्ट नाम प्राप्त करता है। |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | किसी विशिष्ट स्क्रिप्ट टैग को फ़ॉन्ट नाम असाइन करता है, जिससे निर्धारित होता है कि प्रस्तुति में उस स्क्रिप्ट का टेक्स्ट कैसे प्रदर्शित होगा। |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | थीम के फ़ॉन्ट संग्रह से किसी विशिष्ट स्क्रिप्ट टैग से जुड़ी फ़ॉन्ट सेटिंग को हटाता है। |
| [getLatinFont()](#getLatinFont--) | Latin फ़ॉन्ट को लौटाता या सेट करता है। |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin फ़ॉन्ट को लौटाता या सेट करता है। |
| [getEastAsianFont()](#getEastAsianFont--) | East Asian फ़ॉन्ट को लौटाता या सेट करता है। |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | East Asian फ़ॉन्ट को लौटाता या सेट करता है। |
| [getComplexScriptFont()](#getComplexScriptFont--) | जटिल स्क्रिप्ट फ़ॉन्ट को लौटाता या सेट करता है। |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | जटिल स्क्रिप्ट फ़ॉन्ट को लौटाता या सेट करता है। |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

प्रस्तुति में सभी स्क्रिप्ट फ़ॉन्ट परिभाषाओं की शब्दकोश लौटाता है।

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
public final String getScriptFont(String script)
```

प्रस्तुति थीम से किसी विशिष्ट स्क्रिप्ट टैग से जुड़ा फ़ॉन्ट नाम प्राप्त करता है।

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
| script | java.lang.String | व्राइटिंग सिस्टम की पहचान करने के लिए उपयोग किया जाने वाला BCP-47 स्क्रिप्ट कोड (जैसे, "Latn", "Cyrl", "Jpan")। |

**रिटर्न:**
java.lang.String - निर्दिष्ट स्क्रिप्ट के लिए उपयोग में किए गए फ़ॉन्ट का नाम, या  null  यदि स्क्रिप्ट परिभाषित नहीं है।

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

किसी विशिष्ट स्क्रिप्ट टैग को फ़ॉन्ट नाम असाइन करता है, जिससे निर्धारित होता है कि प्रस्तुति में उस स्क्रिप्ट का टेक्स्ट कैसे प्रदर्शित होगा।

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| script | java.lang.String | व्राइटिंग सिस्टम की पहचान करने वाला BCP-47 स्क्रिप्ट कोड (जैसे, "Arab", "Hebr", "Hans")। |
| fontName | java.lang.String | निर्दिष्ट स्क्रिप्ट को असाइन करने के लिए फ़ॉन्ट का नाम। |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

थीम के फ़ॉन्ट संग्रह से किसी विशिष्ट स्क्रिप्ट टैग से जुड़ी फ़ॉन्ट सेटिंग को हटाता है।

--------------------

> ```
> यह उदाहरण दर्शाता है कि हेब्रू स्क्रिप्ट के लिए फ़ॉन्ट मैपिंग को कैसे हटाया जाए:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| script | java.lang.String | वह BCP-47 स्क्रिप्ट कोड जिसका फ़ॉन्ट सेटिंग हटाया जाना चाहिए। |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Latin फ़ॉन्ट को लौटाता या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Latin फ़ॉन्ट को लौटाता या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

East Asian फ़ॉन्ट को लौटाता या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

East Asian फ़ॉन्ट को लौटाता या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

जटिल स्क्रिप्ट फ़ॉन्ट को लौटाता या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**रिटर्न:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

जटिल स्क्रिप्ट फ़ॉन्ट को लौटाता या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |