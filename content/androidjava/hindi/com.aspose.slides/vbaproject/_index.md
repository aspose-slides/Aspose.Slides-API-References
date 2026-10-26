---
title: VbaProject
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: प्रेज़ेंटेशन मैक्रो के साथ VBA प्रोजेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/vbaproject/
---
**विरासत:**  
java.lang.Object

**सबھی लागू इंटरफ़ेस:**  
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

प्रेज़ेंटेशन मैक्रो के साथ VBA प्रोजेक्ट का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [VbaProject()](#VbaProject--) | यह कंस्ट्रक्टर नई VBA प्रोजेक्ट को शून्य से बनाता है। |
| [VbaProject(byte[] data)](#VbaProject-byte---) | यह कंस्ट्रक्टर OLE कंटेनर के बाइनरी प्रतिनिधित्व से VBA प्रोजेक्ट को लोड करता है। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | VBA प्रोजेक्ट का नाम लौटाता है। |
| [getModules()](#getModules--) | VBA प्रोजेक्ट में शामिल सभी मॉड्यूल की सूची लौटाता है। |
| [getReferences()](#getReferences--) | VBA प्रोजेक्ट में शामिल सभी रेफरेंसेस की सूची लौटाता है। |
| [toBinary()](#toBinary--) | VBA प्रोजेक्ट का बाइनरी प्रतिनिधित्व OLE कंटेनर के रूप में लौटाता है। |
| [isPasswordProtected()](#isPasswordProtected--) | बताता है कि VBAProject को प्रोजेक्ट प्रॉपर्टीज़ देखने के लिए पासवर्ड द्वारा संरक्षित किया गया है या नहीं। |

### VbaProject() {#VbaProject--}
```
public VbaProject()
```

यह कंस्ट्रक्टर नई VBA प्रोजेक्ट को शून्य से बनाता है। प्रोजेक्ट 1252 Windows Latin 1 (ANSI) कोडपेज में बनाया जाएगा।

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

यह कंस्ट्रक्टर OLE कंटेनर के बाइनरी प्रतिनिधित्व से VBA प्रोजेक्ट को लोड करता है।

**परामीटर:**
| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```

VBA प्रोजेक्ट का नाम लौटाता है। केवल पढ़ने योग्य String।

**वापसी:**
java.lang.String

### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```

VBA प्रोजेक्ट में शामिल सभी मॉड्यूल की सूची लौटाता है। केवल पढ़ने योग्य [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)।

**वापसी:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)

### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

VBA प्रोजेक्ट में शामिल सभी रेफरेंसेस की सूची लौटाता है। केवल पढ़ने योग्य [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)।

**वापसी:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)

### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

VBA प्रोजेक्ट का बाइनरी प्रतिनिधित्व OLE कंटेनर के रूप में लौटाता है।

**वापसी:**
byte[] - VBA प्रोजेक्ट का बाइनरी प्रतिनिधित्व OLE कंटेनर के रूप में

### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

बताता है कि VBAProject को प्रोजेक्ट प्रॉपर्टीज़ देखने के लिए पासवर्ड द्वारा संरक्षित किया गया है या नहीं। केवल पढ़ने योग्य boolean ।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptm");
>  try {
>      if (presentation.getVbaProject().isPasswordProtected())
>          System.out.println("The VBAProject '" + presentation.getVbaProject().getName() +
>              "' is protected by password to view project properties.");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**वापसी:**
boolean