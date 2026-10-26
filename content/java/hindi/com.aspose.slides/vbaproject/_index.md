---
title: VbaProject
second_title: Aspose.Slides के लिए Java API संदर्भ
description: प्रेजेंटेशन मैक्रो के साथ VBA प्रोजेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/vbaproject/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)  
```
public final class VbaProject implements IVbaProject
```

प्रेजेंटेशन मैक्रो के साथ VBA प्रोजेक्ट का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [VbaProject()](#VbaProject--) | यह कंस्ट्रक्टर नये VBA प्रोजेक्ट को शून्य से बनाता है। |
| [VbaProject(byte[] data)](#VbaProject-byte---) | यह कंस्ट्रक्टर OLE कंटेनर के बाइनरी प्रतिनिधित्व से VBA प्रोजेक्ट लोड करता है। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | VBA प्रोजेक्ट का नाम लौटाता है। |
| [getModules()](#getModules--) | VBA प्रोजेक्ट में सम्मिलित सभी मॉड्यूल की सूची लौटाता है। |
| [getReferences()](#getReferences--) | VBA प्रोजेक्ट में सम्मिलित सभी रेफरेंसेज़ की सूची लौटाता है। |
| [toBinary()](#toBinary--) | VBA प्रोजेक्ट का बाइनरी प्रतिनिधित्व OLE कंटेनर के रूप में लौटाता है। |
| [isPasswordProtected()](#isPasswordProtected--) | क्या VBAProject पासवर्ड द्वारा प्रोजेक्ट प्रॉपर्टीज़ को देखने के लिए संरक्षित है, यह दर्शाता है। |

### VbaProject() {#VbaProject--}
```
public VbaProject()
```

यह कंस्ट्रक्टर शून्य से नया VBA प्रोजेक्ट बनाता है। प्रोजेक्ट 1252 Windows Latin 1 (ANSI) कोडपेज में बनाया जाएगा।

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

यह कंस्ट्रक्टर OLE कंटेनर के बाइनरी प्रतिनिधित्व से VBA प्रोजेक्ट लोड करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```

VBA प्रोजेक्ट का नाम लौटाता है। केवल-केवल String।

**रिटर्न्स:**
java.lang.String

### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```

VBA प्रोजेक्ट में सम्मिलित सभी मॉड्यूल की सूची लौटाता है। केवल-केवल [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)।

**रिटर्न्स:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)

### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

VBA प्रोजेक्ट में सम्मिलित सभी रेफरेंसेज़ की सूची लौटाता है। केवल-केवल [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)।

**रिटर्न्स:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)

### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

VBA प्रोजेक्ट का बाइनरी प्रतिनिधित्व OLE कंटेनर के रूप में लौटाता है।

**रिटर्न्स:**
byte[] - VBA प्रोजेक्ट का बाइनरी प्रतिनिधित्व OLE कंटेनर के रूप में

### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

क्या VBAProject पासवर्ड द्वारा प्रोजेक्ट प्रॉपर्टीज़ को देखने के लिए संरक्षित है, यह दर्शाता है। केवल-केवल boolean।

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


**रिटर्न्स:**
boolean