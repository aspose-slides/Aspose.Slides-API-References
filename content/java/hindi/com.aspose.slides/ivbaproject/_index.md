---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
description: VBA प्रोजेक्ट का प्रतिनिधित्व करता है जिसमें प्रस्तुति मैक्रोज़ होते हैं।
type: docs
url: /hi/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

VBA प्रोजेक्ट का प्रतिनिधित्व करता है जिसमें प्रस्तुति मैक्रोज़ होते हैं।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | VBA प्रोजेक्ट का नाम लौटाता है। |
| [getModules()](#getModules--) | VBA प्रोजेक्ट में शामिल सभी मॉड्यूल की सूची लौटाता है। |
| [getReferences()](#getReferences--) | VBA प्रोजेक्ट में शामिल सभी रेफ़रेंसेज़ की सूची लौटाता है। |
| [toBinary()](#toBinary--) | VBA प्रोजेक्ट का बाइनरी प्रतिनिधित्व OLE कंटेनर के रूप में लौटाता है। |
| [isPasswordProtected()](#isPasswordProtected--) | यह दर्शाता है कि VBAProject को प्रोजेक्ट गुणों को देखने के लिए पासवर्ड द्वारा सुरक्षित किया गया है या नहीं। |
### getName() {#getName--}
```
public abstract String getName()
```

VBA प्रोजेक्ट का नाम लौटाता है। Read-only String.

**Returns:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

VBA प्रोजेक्ट में शामिल सभी मॉड्यूल की सूची लौटाता है। Read-only [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Returns:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

VBA प्रोजेक्ट में शामिल सभी रेफ़रेंसेज़ की सूची लौटाता है। Read-only [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Returns:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

VBA प्रोजेक्ट का बाइनरी प्रतिनिधित्व OLE कंटेनर के रूप में लौटाता है। Read-only byte[].

**Returns:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

यह दर्शाता है कि VBAProject को प्रोजेक्ट गुणों को देखने के लिए पासवर्ड द्वारा सुरक्षित किया गया है या नहीं। Read-only boolean.

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


**Returns:**
boolean