---
title: Merger
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एक ही प्रारूप की कई PowerPoint प्रस्तुतियों को एक फ़ाइल में मिलाने के लिए मेथड्स के समूह को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/merger/
---
**विरासत:**
java.lang.Object
```
public class Merger
```

एक ही प्रारूप की कई PowerPoint प्रस्तुतियों को एक फ़ाइल में मिलाने के लिए मेथड्स का समूह दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | एक ही प्रारूप की कई PowerPoint प्रस्तुतियों को एक एकल प्रस्तुति फ़ाइल में मिलाता है। |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | एक ही प्रारूप की कई PowerPoint प्रस्तुतियों को एक एकल प्रस्तुति फ़ाइल में मिलाता है। |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | एक ही प्रारूप की कई PowerPoint प्रस्तुतियों को एक एकल प्रस्तुति फ़ाइल में मिलाता है। |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | एक ही प्रारूप की कई PowerPoint प्रस्तुतियों को एक एकल प्रस्तुति फ़ाइल में मिलाता है। |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

एक ही प्रारूप की कई PowerPoint प्रस्तुतियों को एक एकल प्रस्तुति फ़ाइल में मिलाता है।

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | इनपुट प्रस्तुति फ़ाइल नामों की एक सरणी। |
| outputFileName | java.lang.String | परिणामी मर्ज की गई प्रस्तुति फ़ाइल का आउटपुट फ़ाइल नाम। |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

एक ही प्रारूप की कई PowerPoint प्रस्तुतियों को एक एकल प्रस्तुति फ़ाइल में मिलाता है।

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | इनपुट प्रस्तुति फ़ाइल नामों की एक सरणी। |
| outputFileName | java.lang.String | परिणामी मर्ज की गई प्रस्तुति फ़ाइल का आउटपुट फ़ाइल नाम। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त विकल्प जो यह निर्धारित करते हैं कि मर्ज की गई प्रस्तुति कैसे सहेजी जाए। |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

एक ही प्रारूप की कई PowerPoint प्रस्तुतियों को एक एकल प्रस्तुति फ़ाइल में मिलाता है।

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | इनपुट प्रस्तुति फ़ाइल नामों की एक सरणी। |
| outputStream | java.io.OutputStream | आउटपुट स्ट्रीम। |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

एक ही प्रारूप की कई PowerPoint प्रस्तुतियों को एक एकल प्रस्तुति फ़ाइल में मिलाता है।

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | इनपुट प्रस्तुति फ़ाइल नामों की एक सरणी। |
| outputStream | java.io.OutputStream | आउटपुट स्ट्रीम। |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | अतिरिक्त विकल्प जो यह निर्धारित करते हैं कि मर्ज की गई प्रस्तुति कैसे सहेजी जाए। |