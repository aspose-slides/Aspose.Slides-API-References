---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides for Android जावा API संदर्भ के माध्यम से
description: एक अपरिवर्तनीय ऑब्जेक्ट जो चित्र भराव के गुणों को समाहित करता है।
type: docs
url: /hi/com.aspose.slides/ipicturefillformateffectivedata/
---
**सभी लागू इंटरफेस:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

एक अपरिवर्तनीय ऑब्जेक्ट जो चित्र भराव के गुणों को शामिल करता है।

--------------------

यह इंटरफ़ेस [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) का भाग के रूप में उपयोग किया जाता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getDpi()](#getDpi--) | चित्र भरने के लिए उपयोग किए जाने वाले dpi को लौटाता है। |
| [getPictureFillMode()](#getPictureFillMode--) | चित्र भराव मोड को लौटाता है। |
| [getPicture()](#getPicture--) | चित्र को लौटाता है। |
| [getCropLeft()](#getCropLeft--) | चित्र के बाएँ भाग से क्रॉप किए गए वास्तविक छवि चौड़ाई के प्रतिशत को लौटाता है। |
| [getCropTop()](#getCropTop--) | चित्र के शीर्ष भाग से क्रॉप किए गए वास्तविक छवि ऊँचाई के प्रतिशत को लौटाता है। |
| [getCropRight()](#getCropRight--) | चित्र के दाएँ भाग से क्रॉप किए गए वास्तविक छवि चौड़ाई के प्रतिशत को लौटाता है। |
| [getCropBottom()](#getCropBottom--) | चित्र के नीचे भाग से क्रॉप किए गए वास्तविक छवि ऊँचाई के प्रतिशत को लौटाता है। |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

चित्र भरने के लिए उपयोग किए जाने वाले dpi को लौटाता है। Read-only int.

**रिटर्न:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

चित्र भराव मोड को लौटाता है। केवल-पढ़ने-योग्य [PictureFillMode](../../com.aspose.slides/picturefillmode)।

**रिटर्न:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

चित्र को लौटाता है। केवल-पढ़ने-योग्य [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)।

**रिटर्न:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

चित्र के बाएँ भाग से क्रॉप किए गए वास्तविक छवि चौड़ाई के प्रतिशत को लौटाता है। केवल-पढ़ने-योग्य float।

**रिटर्न:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

चित्र के शीर्ष भाग से क्रॉप किए गए वास्तविक छवि ऊँचाई के प्रतिशत को लौटाता है। केवल-पढ़ने-योग्य float।

**रिटर्न:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

चित्र के दाएँ भाग से क्रॉप किए गए वास्तविक छवि चौड़ाई के प्रतिशत को लौटाता है। केवल-पढ़ने-योग्य float।

**रिटर्न:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

चित्र के नीचे भाग से क्रॉप किए गए वास्तविक छवि ऊँचाई के प्रतिशत को लौटाता है। केवल-पढ़ने-योग्य float।

**रिटर्न:**
float