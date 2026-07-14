---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: खोज पाठ परिणाम प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस।
type: docs
url: /hi/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

खोज पाठ परिणाम प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | कॉलबैक मेथड जो पाए गए पाठ के बारे में डेटा प्राप्त करता है। |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

कॉलबैक मेथड जो पाए गए पाठ के बारे में डेटा प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | पाठ जिस [ITextFrame](../../com.aspose.slides/itextframe) में मिला था। |
| sourceText | java.lang.String | स्रोत पाठ जिसमें पाठ मिला था। |
| foundText | java.lang.String | पाया गया पाठ। |
| textPosition | int | पाए गए पाठ की स्थिति। |