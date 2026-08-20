---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /hi/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

\#SvgImageSavingDelegate.SvgImageSavingDelegate घटना के Markdown SVG छवि सहेजने हैंडलर को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Markdown निर्यात के दौरान प्रत्येक SVG छवि के लिए बुलाया जाता है। |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```


Markdown निर्यात के दौरान प्रत्येक SVG छवि के लिए बुलाया जाता है। निर्दिष्ट लिंक का उपयोग करने के लिए true लौटाएँ, या डिफ़ॉल्ट सहेजने की तर्क को लागू करने के लिए false लौटाएँ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | निर्यात की जा रही SVG छवि। |
| link | java.lang.String[] | जब true लौटाया जाए तो उपयोग करने के लिए Markdown लिंक। |

**रिटर्न मान:**
boolean