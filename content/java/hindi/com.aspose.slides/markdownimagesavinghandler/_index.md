---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /hi/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

\#ImageSavingDelegate.ImageSavingDelegate इवेंट का markdown इमेज सहेजने वाला हैंडलर दर्शाता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Markdown निर्यात के दौरान प्रत्येक गैर-SVG छवि (बिटमैप या मेटाफाइल) के लिए बुलाया जाता है। |

### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Markdown निर्यात के दौरान प्रत्येक गैर-SVG छवि (बिटमैप या मेटाफाइल) के लिए बुलाया जाता है। निर्दिष्ट लिंक का उपयोग करने के लिए true लौटाएँ, या डिफ़ॉल्ट सहेजने तर्क लागू करने के लिए false लौटाएँ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | एक्सपोर्ट की जा रही छवि (बिटमैप या मेटाफाइल)। |
| format | int | छवि प्रारूप। |
| link | java.lang.String[] | वापसी true होने पर उपयोग करने वाला Markdown लिंक। |

**रिटर्न:**
boolean