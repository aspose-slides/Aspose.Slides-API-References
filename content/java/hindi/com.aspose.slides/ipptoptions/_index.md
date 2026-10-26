---
title: IPptOptions
second_title: Java API संदर्भ के लिए Aspose.Slides
description: विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति PPT प्रारूप में कैसे सहेजी जाती है।
type: docs
url: /hi/com.aspose.slides/ipptoptions/
---
**सभी लागू इंटरफेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

ऐसे विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति PPT फ़ॉर्मेट में कैसे सहेजी जाती है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | प्रतिनिधित्व करता है ऑब्जेक्ट क्लास GUID (CLSID) जिसे रूट डायरेक्टरी एंट्री में संग्रहित किया गया है। |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | प्रतिनिधित्व करता है ऑब्जेक्ट क्लास GUID (CLSID) जिसे रूट डायरेक्टरी एंट्री में संग्रहित किया गया है। |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```


प्रतिनिधित्व करता है ऑब्जेक्ट क्लास GUID (CLSID) जिसे रूट डायरेक्टरी एंट्री में संग्रहित किया गया है। दस्तावेज़ के एप्लिकेशन की COM सक्रियण के लिए उपयोग किया जा सकता है। डिफ़ॉल्ट मान '64818D11-4F9B-11CF-86EA-00AA00B929E8' है जो 'Microsoft Powerpoint.Slide.8' के अनुरूप है।

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
public abstract void setRootDirectoryClsid(UUID value)
```


प्रतिनिधित्व करता है ऑब्जेक्ट क्लास GUID (CLSID) जिसे रूट डायरेक्टरी एंट्री में संग्रहित किया गया है। दस्तावेज़ के एप्लिकेशन की COM सक्रियण के लिए उपयोग किया जा सकता है। डिफ़ॉल्ट मान '64818D11-4F9B-11CF-86EA-00AA00B929E8' है जो 'Microsoft Powerpoint.Slide.8' के अनुरूप है।

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