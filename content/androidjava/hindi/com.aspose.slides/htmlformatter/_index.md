---
title: HtmlFormatter
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: HTML फ़ाइल टेम्प्लेट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/htmlformatter/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)  
```
public final class HtmlFormatter implements IHtmlFormatter
```

HTML फ़ाइल टेम्पलेट का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | एक सरल दस्तावेज़ दृश्य के लिए HTML फॉर्मेटर बनाता और लौटाता है, जिसमें स्लाइड्स की श्रृंखला एक के नीचे एक होती है। |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | एक सरल स्लाइड शो HTML के लिए HTML फॉर्मेटर बनाता और लौटाता है, जो स्लाइड्स को क्रम क्रम से दिखाता है। |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | कस्टम कॉलबैक-ड्रिवन HTML जनरेशन के लिए HTML फॉर्मेटर बनाता और लौटाता है। |

### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

एक सरल दस्तावेज़ दृश्य के लिए HTML फॉर्मेटर बनाता और लौटाता है, जिसमें स्लाइड्स की श्रृंखला एक के नीचे एक होती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| css | java.lang.String | इस फ़ाइल के लिए CSS निर्दिष्ट करता है। |
| showSlideTitle | boolean | यदि स्लाइड छवि के ऊपर स्लाइड शीर्षक हो तो उसे जोड़ें। |

**रिटर्न:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) ऑब्जेक्ट।

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

एक सरल स्लाइड शो HTML के लिए HTML फॉर्मेटर बनाता और लौटाता है, जो स्लाइड्स को क्रम क्रम से दिखाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| css | java.lang.String | उपयोग किए गए CCS फ़ाइल का URL निर्दिष्ट करता है। |
| showSlideTitle | boolean | यदि स्लाइड छवि के ऊपर स्लाइड शीर्षक हो तो उसे जोड़ें। |

**रिटर्न:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) ऑब्जेक्ट।

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

कस्टम कॉलबैक-ड्रिवन HTML जनरेशन के लिए HTML फॉर्मेटर बनाता और लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | कॉलबैक इंटरफ़ेस जो HTML फ़ाइल जनरेशन को नियंत्रित करता है। |

**रिटर्न:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) ऑब्जेक्ट।