---
title: VbaReferenceFactory
second_title: Aspose.Slides for Java API संदर्भ
description: COM इंटरफ़ेस के माध्यम से VBA प्रोजेक्ट रेफ़रेंसेज़ बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/vbareferencefactory/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

COM इंटरफ़ेस के माध्यम से VBA प्रोजेक्ट रेफ़रेंसेज़ बनाने की अनुमति देता है
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getInstance()](#getInstance--) | VBA प्रोजेक्ट रेफ़रेंसेज़ फ़ैक्टरी स्थिर उदाहरण। |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | नया OLE Automation टाइप लाइब्रेरी रेफ़रेंस बनाता है। |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


VBA प्रोजेक्ट रेफ़रेंसेज़ फ़ैक्टरी स्थिर उदाहरण। केवल पढ़ने योग्य [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)।

**Returns:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

नया OLE Automation टाइप लाइब्रेरी रेफ़रेंस बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Returns:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - नया OLE Automation टाइप लाइब्रेरी रेफ़रेंस