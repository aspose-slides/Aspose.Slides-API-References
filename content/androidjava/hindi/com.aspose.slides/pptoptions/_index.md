---
title: PptOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: विकल्प प्रदान करता है जो यह नियंत्रित करते हैं कि प्रस्तुति PPT प्रारूप में कैसे सहेजी जाती है।
type: docs
url: /hi/com.aspose.slides/pptoptions/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable  
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

प्रस्तुति को PPT प्रारूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Represents the object class GUID (CLSID) that is stored in the root directory entry. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Represents the object class GUID (CLSID) that is stored in the root directory entry. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```


### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```

रूट डायरेक्टरी एंट्री में संग्रहीत ऑब्जेक्ट क्लास GUID (CLSID) को दर्शाता है। दस्तावेज़ के एप्लिकेशन की COM सक्रियता के लिए उपयोग किया जा सकता है। डिफ़ॉल्ट मान '64818D11-4F9B-11CF-86EA-00AA00B929E8' है जो 'Microsoft Powerpoint.Slide.8' से मेल खाता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID को 'Microsoft Powerpoint.Show.8' पर सेट करें
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**  
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```

रूट डायरेक्टरी एंट्री में संग्रहीत ऑब्जेक्ट क्लास GUID (CLSID) को दर्शाता है। दस्तावेज़ के एप्लिकेशन की COM सक्रियता के लिए उपयोग किया जा सकता है। डिफ़ॉल्ट मान '64818D11-4F9B-11CF-86EA-00AA00B929E8' है जो 'Microsoft Powerpoint.Slide.8' से मेल खाता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID को 'Microsoft Powerpoint.Show.8' पर सेट करें
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.UUID |  |