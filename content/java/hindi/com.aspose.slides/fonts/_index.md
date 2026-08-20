---
title: Fonts
second_title: Aspose.Slides for Java API संदर्भ
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
| [getScriptFontMap()](#getScriptFontMap--) | प्रेज़ेंटेशन में सभी स्क्रिप्ट फ़ॉन्ट परिभाषाओं का एक शब्दकोश लौटाता है। |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | प्रेज़ेंटेशन थीम से एक विशिष्ट स्क्रिप्ट टैग से जुड़ा फ़ॉन्ट नाम प्राप्त करता है। |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | एक विशिष्ट स्क्रिप्ट टैग को फ़ॉन्ट नाम असाइन करता है, जो निर्धारित करता है कि उस स्क्रिप्ट के टेक्स्ट को प्रेज़ेंटेशन में कैसे रेंडर किया जाएगा। |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | थीम के फ़ॉन्ट संग्रह से एक विशिष्ट स्क्रिप्ट टैग से जुड़ी फ़ॉन्ट सेटिंग को हटाता है। |
| [getLatinFont()](#getLatinFont--) | Latin फ़ॉन्ट को लौटाता है या सेट करता है। |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin फ़ॉन्ट को लौटाता है या सेट करता है। |
| [getEastAsianFont()](#getEastAsianFont--) | East Asian फ़ॉन्ट को लौटाता है या सेट करता है। |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | East Asian फ़ॉन्ट को लौटाता है या सेट करता है। |
| [getComplexScriptFont()](#getComplexScriptFont--) | जटिल स्क्रिप्ट फ़ॉन्ट को लौटाता है या सेट करता है। |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | जटिल स्क्रिप्ट फ़ॉन्ट को लौटाता है या सेट करता है। |

### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

प्रेज़ेंटेशन में सभी स्क्रिप्ट फ़ॉन्ट परिभाषाओं का एक शब्दकोश लौटाता है।

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**वापसी:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - एक शब्दकोश जो स्क्रिप्ट कोड्स को फ़ॉन्ट नामों से मैप करता है।

### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

प्रेज़ेंटेशन थीम से एक विशिष्ट स्क्रिप्ट टैग से जुड़ा फ़ॉन्ट नाम प्राप्त करता है।

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| script | java.lang.String | लेखन प्रणाली की पहचान करने के लिए प्रयुक्त BCP-47 स्क्रिप्ट कोड (उदाहरण के लिए, "Latn", "Cyrl", "Jpan")। |

**वापसी:**
java.lang.String - निर्दिष्ट स्क्रिप्ट के लिए प्रयुक्त फ़ॉन्ट का नाम, या यदि स्क्रिप्ट परिभाषित नहीं है तो  null  ।

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

एक विशिष्ट स्क्रिप्ट टैग को फ़ॉन्ट नाम असाइन करता है, जो निर्धारित करता है कि उस स्क्रिप्ट के टेक्स्ट को प्रेज़ेंटेशन में कैसे रेंडर किया जाएगा।

--------------------

> ```
> यह उदाहरण दिखाता है कि अरबी स्क्रिप्ट के लिए फ़ॉन्ट को "Segoe UI" कैसे सेट किया जाए:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| script | java.lang.String | लेखन प्रणाली की पहचान करने वाला BCP-47 स्क्रिप्ट कोड (उदाहरण के लिए, "Arab", "Hebr", "Hans")। |
| fontName | java.lang.String | निर्दिष्ट स्क्रिप्ट को असाइन करने के लिये फ़ॉन्ट का नाम। |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

थीम के फ़ॉन्ट संग्रह से एक विशिष्ट स्क्रिप्ट टैग से जुड़ी फ़ॉन्ट सेटिंग को हटाता है।

--------------------

> ```
> यह उदाहरण दिखाता है कि हिब्रू स्क्रिप्ट के लिए फ़ॉन्ट मैपिंग को कैसे हटाया जाए:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| script | java.lang.String | BCP-47 स्क्रिप्ट कोड जिसकी फ़ॉन्ट सेटिंग हटाई जानी चाहिए। |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Latin फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**वापसी:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Latin फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

East Asian फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**वापसी:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

East Asian फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

जटिल स्क्रिप्ट फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**वापसी:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

जटिल स्क्रिप्ट फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |