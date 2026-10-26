---
title: SvgImage
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक SVG छवि का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/svgimage/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

एक SVG छवि का प्रतिनिधित्व करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | नया SvgImage वस्तु बनाता है। |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | नया SvgImage वस्तु बनाता है। |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | नया SvgImage वस्तु बनाता है। |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | नया SvgImage वस्तु बनाता है। |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | नया SvgImage वस्तु बनाता है। |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | नया SvgImage वस्तु बनाता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSvgData()](#getSvgData--) | SVG डेटा लौटाता है। |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | SVG दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिये उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस लौटाता है। |
| [getBaseUri()](#getBaseUri--) | निर्धारित SVG के आधार URI को लौटाता है। |
| [getSvgContent()](#getSvgContent--) | SVG सामग्री लौटाता है। |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | SVG छवि को EMF फ़ाइल के रूप में सहेजता है। |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```


नया SvgImage वस्तु बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | Svg डेटा। |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```


नया SvgImage वस्तु बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgContent | java.lang.String | Svg सामग्री। |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


नया SvgImage वस्तु बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | Svg स्ट्रीम। |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```


नया SvgImage वस्तु बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | Svg डेटा। |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को लाने के लिये उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| baseUri | java.lang.String | निर्धारित SVG के आधार URI। सापेक्ष लिंक को हल करने के लिये प्रयुक्त। |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```


नया SvgImage वस्तु बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgContent | java.lang.String | Svg सामग्री। |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को लाने के लिये उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| baseUri | java.lang.String | निर्धारित SVG के आधार URI। सापेक्ष लिंक को हल करने के लिये प्रयुक्त। |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```


नया SvgImage वस्तु बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | Svg स्ट्रीम। |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | बाहरी वस्तुओं को लाने के लिये उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| baseUri | java.lang.String | निर्धारित SVG के आधार URI। सापेक्ष लिंक को हल करने के लिये प्रयुक्त। |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```


SVG डेटा लौटाता है। केवल पढ़ने योग्य byte[]।

**वापसी:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```


SVG दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिये उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस लौटाता है। केवल पढ़ने योग्य [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)।

**वापसी:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```


निर्धारित SVG के आधार URI को लौटाता है। सापेक्ष लिंक को हल करने के लिये प्रयुक्त। केवल पढ़ने योग्य String।

**वापसी:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```


SVG सामग्री लौटाता है। केवल पढ़ने योग्य String।

**वापसी:**
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
>  // SVG छवि को एक metafille के रूप में सहेजता है
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
>      // SVG छवि को एक metafille के रूप में सहेजता है
>      svgImage.writeAsEmf(byteStream);
>      // इमेज कलेक्शन में metafile जोड़ता है
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |