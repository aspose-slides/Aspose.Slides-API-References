---
title: IFindResultCallback
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to getting search text result.
type: docs
url: /hi/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

सर्च टेक्स्ट परिणाम प्राप्त करने के लिए प्रयुक्त कॉलबैक इंटरफ़ेस।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | पाया गया टेक्स्ट के बारे में डेटा प्राप्त करने वाला कॉलबैक मेथड। |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

पाया गया टेक्स्ट के बारे में डेटा प्राप्त करने वाला कॉलबैक मेथड।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | जिस [ITextFrame](../../com.aspose.slides/itextframe) में टेक्स्ट मिला था। |
| sourceText | java.lang.String | स्रोत टेक्स्ट जिसमें टेक्स्ट मिला था। |
| foundText | java.lang.String | पाया गया टेक्स्ट। |
| textPosition | int | पाए गए टेक्स्ट की स्थिति। |