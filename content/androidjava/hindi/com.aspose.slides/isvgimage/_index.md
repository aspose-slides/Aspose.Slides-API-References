---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an SVG image.
type: docs
url: /hi/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

एक SVG छवि का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | SVG सामग्री लौटाता है। |
| [getSvgData()](#getSvgData--) | SVG डेटा लौटाता है। |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | SVG दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस लौटाता है। |
| [getBaseUri()](#getBaseUri--) | निर्दिष्ट SVG का बेस URI लौटाता है। |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | SVG छवि को EMF फ़ाइल के रूप में सहेजता है। |

### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```

SVG सामग्री लौटाता है। केवल-पढ़ने योग्य String.

**रिटर्न:**
java.lang.String

### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```

SVG डेटा लौटाता है। केवल-पढ़ने योग्य byte[].

**रिटर्न:**
byte[]

### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```

SVG दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस लौटाता है। केवल-पढ़ने योग्य [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**रिटर्न:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)

### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```

निर्दिष्ट SVG का बेस URI लौटाता है। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। केवल-पढ़ने योग्य String.

**रिटर्न:**
java.lang.String

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

SVG छवि को EMF फ़ाइल के रूप में सहेजता है।

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // नए SVG छवि बनाता है
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // SVG छवि को एक मेटाफाइल के रूप में सहेजता है
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // नए SVG छवि बनाता है
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // SVG छवि को एक मेटाफाइल के रूप में सहेजता है
>      svgImage.writeAsEmf(byteStream);
>      // इमेज कलेक्शन में मेटाफाइल जोड़ता है
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |