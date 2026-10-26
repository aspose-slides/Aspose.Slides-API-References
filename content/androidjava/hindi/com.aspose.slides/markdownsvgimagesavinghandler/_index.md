---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस
description: SvgImageSavingDelegate.SvgImageSavingDelegate इवेंट के markdown SVG इमेज सेविंग हैंडलर का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

\#SvgImageSavingDelegate.SvgImageSavingDelegate इवेंट के markdown SVG इमेज सेविंग हैंडलर का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Markdown निर्यात के दौरान प्रत्येक SVG इमेज के लिए कॉल किया जाता है। |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Markdown निर्यात के दौरान प्रत्येक SVG इमेज के लिए कॉल किया जाता है। निर्दिष्ट लिंक का उपयोग करने के लिए true लौटाएँ, या डिफॉल्ट सहेजने तर्क को लागू करने के लिए false।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | निर्यात हो रही SVG इमेज। |
| link | java.lang.String[] | जब true लौटाया जाए तो उपयोग करने के लिए Markdown लिंक। |

**वापसी मान:**
boolean