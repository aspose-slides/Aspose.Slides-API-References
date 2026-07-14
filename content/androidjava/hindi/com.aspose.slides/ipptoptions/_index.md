---
title: IPptOptions
second_title: Aspose.Slides के लिए Android, Java API रेफ़रेंस के माध्यम से
description: विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति PPT फ़ॉर्मेट में कैसे सहेजी जाती है।
type: docs
url: /hi/com.aspose.slides/ipptoptions/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति PPT स्वरूप में कैसे सहेजी जाती है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | ऑब्जेक्ट क्लास GUID (CLSID) को दर्शाता है जो रूट डायरेक्टरी एंट्री में संग्रहीत है। |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | ऑब्जेक्ट क्लास GUID (CLSID) को दर्शाता है जो रूट डायरेक्टरी एंट्री में संग्रहीत है। |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```


ऑब्जेक्ट क्लास GUID (CLSID) को दर्शाता है जो रूट डायरेक्टरी एंट्री में संग्रहीत है। दस्तावेज़ के अनुप्रयोग की COM सक्रियता के लिए उपयोग किया जा सकता है। डिफ़ॉल्ट मान '64818D11-4F9B-11CF-86EA-00AA00B929E8' है जो 'Microsoft Powerpoint.Slide.8' से मेल खाता है।

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


ऑब्जेक्ट क्लास GUID (CLSID) को दर्शाता है जो रूट डायरेक्टरी एंट्री में संग्रहीत है। दस्तावेज़ के अनुप्रयोग की COM सक्रियता के लिए उपयोग किया जा सकता है। डिफ़ॉल्ट मान '64818D11-4F9B-11CF-86EA-00AA00B929E8' है जो 'Microsoft Powerpoint.Slide.8' से मेल खाता है।

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