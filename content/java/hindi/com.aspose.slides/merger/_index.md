---
title: Merger
second_title: Aspose.Slides for Java API संदर्भ
description: एक ही फ़ॉर्मेट की कई PowerPoint प्रस्तुतियों को एक फ़ाइल में मिलाने के लिए मेथड्स का समूह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/merger/
---
**विरासत:**  
java.lang.Object  
```
public class Merger
```

एक ही फ़ॉर्मेट की कई PowerPoint प्रस्तुतियों को एक फ़ाइल में मिलाने के लिए मेथड्स का समूह दर्शाता है।  
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | एक ही फ़ॉर्मेट की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है। |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | एक ही फ़ॉर्मेट की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है। |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | एक ही फ़ॉर्मेट की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है। |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | एक ही फ़ॉर्मेट की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है। |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

एक ही फ़ॉर्मेट की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है।

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | इनपुट प्रस्तुति फ़ाइल नामों का एक ऐरे। |
| outputFileName | java.lang.String | परिणामी मर्ज्ड प्रस्तुति फ़ाइल का आउटपुट फ़ाइल नाम। |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

एक ही फ़ॉर्मेट की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है।

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | इनपुट प्रस्तुति फ़ाइल नामों का एक ऐरे। |
| outputFileName | java.lang.String | परिणामी मर्ज्ड प्रस्तुति फ़ाइल का आउटपुट फ़ाइल नाम। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त विकल्प जो यह निर्धारित करते हैं कि मर्ज्ड प्रस्तुति कैसे सहेजी जाती है। |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

एक ही फ़ॉर्मेट की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है।

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | इनपुट प्रस्तुति फ़ाइल नामों का एक ऐरे। |
| outputStream | java.io.OutputStream | आउटपुट स्ट्रीम। |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

एक ही फ़ॉर्मेट की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है।

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | इनपुट प्रस्तुति फ़ाइल नामों का एक ऐरे। |
| outputStream | java.io.OutputStream | आउटपुट स्ट्रeam। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त विकल्प जो यह निर्धारित करते हैं कि मर्ज्ड प्रस्तुति कैसे सहेजी जाती है। |