---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /hi/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

ImageSavingDelegate.ImageSavingDelegate इवेंट के markdown image saving handler को दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Invoked for each non-SVG image (bitmap or metafile) during Markdown export. |

### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Markdown निर्यात के दौरान प्रत्येक non-SVG छवि (bitmap या metafile) के लिए कॉल किया जाता है। true लौटाएँ ताकि निर्दिष्ट लिंक का उपयोग किया जा सके, या false लौटाएँ ताकि डिफ़ॉल्ट सहेजने की लॉजिक लागू हो।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | निर्यात हो रही छवि (bitmap या metafile)। |
| format | int | छवि का फॉर्मेट। |
| link | java.lang.String[] | true लौटाने पर उपयोग करने के लिए Markdown लिंक। |

**रिटर्न वैल्यू:**
boolean