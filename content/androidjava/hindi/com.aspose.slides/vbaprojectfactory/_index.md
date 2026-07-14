---
title: VbaProjectFactory
second_title: Aspose.Slides for Android के लिए Java API रेफरेंस के माध्यम से
description: COM इंटरफ़ेस के माध्यम से VBA प्रोजेक्ट बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/vbaprojectfactory/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

COM इंटरफ़ेस के माध्यम से VBA प्रोजेक्ट बनाने की अनुमति देता है
## निर्माताओं

| निर्माता | विवरण |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getInstance()](#getInstance--) | VBA प्रोजेक्ट फ़ैक्टरी स्थिर उदाहरण। |
| [createVbaProject()](#createVbaProject--) | नया VBA प्रोजेक्ट बनाता है। |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | OLE कंटेनर से VBA प्रोजेक्ट पढ़ता है। |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBA प्रोजेक्ट फ़ैक्टरी स्थिर उदाहरण। केवल-पढ़ने योग्य [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)।

**रिटर्न:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


नया VBA प्रोजेक्ट बनाता है।

**रिटर्न:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - नया VBA प्रोजेक्ट
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


OLE कंटेनर से VBA प्रोजेक्ट पढ़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] |  |

**रिटर्न:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - पढ़ा गया VBA प्रोजेक्ट