---
title: SvgImage
second_title: Aspose.Slides for Java API संदर्भ
description: एक SVG छवि का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/svgimage/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)  
```
public class SvgImage implements ISvgImage
```

एक SVG छवि का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Creates new SvgImage object. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Creates new SvgImage object. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates new SvgImage object. |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getSvgData()](#getSvgData--) | Returns SVG data. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Return callback interface used to resolve external resources during Svg documents import. |
| [getBaseUri()](#getBaseUri--) | Returns base URI of the specified Svg. |
| [getSvgContent()](#getSvgContent--) | Returns SVG content. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Saves the SVG image as an EMF file. |

### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

एक नया SvgImage ऑब्जेक्ट बनाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| data | byte[] | SVG डेटा। |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

एक नया SvgImage ऑब्जेक्ट बनाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| svgContent | java.lang.String | SVG सामग्री। |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

एक नया SvgImage ऑब्जेक्ट बनाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | SVG स्ट्रीम। |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

एक नया SvgImage ऑब्जेक्ट बनाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| data | byte[] | SVG डेटा। |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स को लाने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को नजरअंदाज़ किया जाएगा। |
| baseUri | java.lang.String | निर्दिष्ट SVG का बेस URI। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

एक नया SvgImage ऑब्जेक्ट बनाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| svgContent | java.lang.String | SVG सामग्री। |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स को लाने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को नजरअंदाज़ किया जाएगा। |
| baseUri | java.lang.String | निर्दिष्ट SVG का बेस URI। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

एक नया SvgImage ऑब्जेक्ट बनाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | SVG स्ट्रीम। |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स को लाने के लिए उपयोग किया जाने वाला कॉلبैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को नजरअंदाज़ किया जाएगा। |
| baseUri | java.lang.String | निर्दिष्ट SVG का बेस URI। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

SVG डेटा लौटाता है। केवल पढ़ने योग्य byte[]।

**रिटर्न:**
byte[]

### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Svg दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस लौटाता है। केवल पढ़ने योग्य [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)।

**रिटर्न:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)

### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

निर्दिष्ट SVG का बेस URI लौटाता है। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। केवल पढ़ने योग्य String।

**रिटर्न:**
java.lang.String

### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

SVG सामग्री लौटाता है। केवल पढ़ने योग्य String।

**रिटर्न:**
java.lang.String

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

SVG छवि को EMF फ़ाइल के रूप में सहेजता है।

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // नई SVG छवि बनाता है
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // SVG छवि को एक मेटा फ़ाइल के रूप में सहेजता है
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // नई SVG छवि बनाता है
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // SVG छवि को एक मेटा फ़ाइल के रूप में सहेजता है
>      svgImage.writeAsEmf(byteStream);
>      // इमेज कलेक्शन में मेटा फ़ाइल जोड़ता है
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | टार्गेट स्ट्रीम |