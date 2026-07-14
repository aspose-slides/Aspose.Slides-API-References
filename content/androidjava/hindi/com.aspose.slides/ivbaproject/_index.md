---
title: IVbaProject
second_title: Aspose.Slides for Android via Java API Reference
description: Represents VBA project with presentation macros.
type: docs
url: /hi/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

प्रेजेंटेशन मैक्रोज़ के साथ VBA प्रोजेक्ट का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | VBA प्रोजेक्ट का नाम लौटाता है। |
| [getModules()](#getModules--) | VBA प्रोजेक्ट में सम्मिलित सभी मॉड्यूल की सूची लौटाता है। |
| [getReferences()](#getReferences--) | VBA प्रोजेक्ट में सम्मिलित सभी रेफ़रेंसेज़ की सूची लौटाता है। |
| [toBinary()](#toBinary--) | VBA प्रोजेक्ट का बाइनरी प्रतिनिधित्व OLE कंटेनर के रूप में लौटाता है। |
| [isPasswordProtected()](#isPasswordProtected--) | यह दर्शाता है कि क्या VBAProject को प्रोजेक्ट गुण देखने के लिये पासवर्ड द्वारा सुरक्षित किया गया है। |
### getName() {#getName--}
```
public abstract String getName()
```


VBA प्रोजेक्ट का नाम लौटाता है। केवल-पढ़ने-योग्य String.

**Returns:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


VBA प्रोजेक्ट में सम्मिलित सभी मॉड्यूल की सूची लौटाता है। केवल-पढ़ने-योग्य [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)।

**Returns:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


VBA प्रोजेक्ट में सम्मिलित सभी रेफ़रेंसेज़ की सूची लौटाता है। केवल-पढ़ने-योग्य [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)।

**Returns:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


VBA प्रोजेक्ट का बाइनरी प्रतिनिधित्व OLE कंटेनर के रूप में लौटाता है। केवल-पढ़ने-योग्य byte[]।

**Returns:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


यह दर्शाता है कि क्या VBAProject को प्रोजेक्ट गुण देखने के लिये पासवर्ड द्वारा सुरक्षित किया गया है। केवल-पढ़ने-योग्य boolean.

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