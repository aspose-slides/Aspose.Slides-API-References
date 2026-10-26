---
title: VbaReferenceFactory
second_title: Java API रेफ़रेंस के माध्यम से Aspose.Slides for Android
description: COM इंटरफ़ेस के माध्यम से VBA प्रोजेक्ट रेफ़रेंसेज़ बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/vbareferencefactory/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफेस:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

COM इंटरफ़ेस के माध्यम से VBA प्रोजेक्ट रेफ़रेंसेज़ बनाने की अनुमति देता है
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getInstance()](#getInstance--) | VBA प्रोजेक्ट रेफ़रेंसेज़ फ़ैक्टरी स्थिर इंस्टेंस। |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | नई OLE ऑटॉमेशन टाइप लाइब्रेरी रेफ़रेंसेज़ बनाता है। |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


VBA प्रोजेक्ट रेफ़रेंसेज़ फ़ैक्टरी स्थिर इंस्टेंस। केवल पढ़ने योग्य [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)।

**वापसी:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


नया OLE ऑटॉमेशन टाइप लाइब्रेरी रेफ़रेंसेज़ बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**वापसी:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - नया OLE ऑटॉमेशन टाइप लाइब्रेरी रेफ़रेंसेज़