---
title: VideoPlayerHtmlController
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: यह क्लास वीडियो और ऑडियो फ़ाइलों को HTML में निर्यात करने की अनुमति देती है
type: docs
url: /hi/com.aspose.slides/videoplayerhtmlcontroller/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

यह क्लास वीडियो और ऑडियो फ़ाइलों को HTML में निर्यात करने की अनुमति देती है
## कन्स्ट्रक्टर

| Constructor | Description |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | कंट्रोलर का नया उदाहरण बनाता है |
## मेथड्स

| Method | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) |  |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) |  |
| [getUrl(int id, int referrer)](#getUrl-int-int-) |  |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) |  |
### VideoPlayerHtmlController(String path, String fileName, String baseUri) {#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-}
```
public VideoPlayerHtmlController(String path, String fileName, String baseUri)
```


नियंत्रक का नया उदाहरण बनाता है

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | वह पथ जहाँ वीडियो और ऑडियो फ़ाइलें उत्पन्न की जाएँगी |
| fileName | java.lang.String | HTML फ़ाइल का नाम |
| baseUri | java.lang.String | लिंक उत्पन्न करने के लिए उपयोग किया जाने वाला बेस URI |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


HTML दस्तावेज़ हेडर लिखने के लिए बुलाया जाता है। प्रस्तुति रूपांतरण में प्रत्येक बार एक बार बुलाया जाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


HTML दस्तावेज़ फुटर लिखने के लिए बुलाया जाता है। प्रस्तुति रूपांतरण में प्रत्येक बार एक बार बुलाया जाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


HTML स्लाइड हेडर लिखने के लिए बुलाया जाता है। प्रत्येक स्लाइड के लिए एक बार बुलाया जाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


HTML स्लाइड फुटर लिखने के लिए बुलाया जाता है। प्रत्येक स्लाइड के लिए एक बार बुलाया जाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


शेप के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक शेप के लिए एक बार बुलाया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज निर्माण समाप्त हो जाएगा, जोड़ा गया HTML टुकड़ा सम्मिलित होगा और नई इमेज पिछले के ऊपर शुरू होगी।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


शेप के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक शेप के लिए एक बार बुलाया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इिमेज निर्माण समाप्त हो जाएगा, जोड़ा गया HTML टुकड़ा सम्मिलित होगा और नई इमेज पिछले के ऊपर शुरू होगी।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```


यह फ़ंक्शन शेप को SVG में रेंडर करने से पहले बुलाया जाता है ताकि उपयोगकर्ता परिणामस्वरूप SVG को नियंत्रित कर सके।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


निर्धारित करता है कि ऑब्जेक्ट को कहाँ संग्रहीत किया जाना चाहिए। यह मेथड प्रत्येक ऑब्जेक्ट आईडी के लिए एक बार बुलाया जाता है। यह गारंटी नहीं है कि समान डेटा, semanticName और contentType वाले दो ऑब्जेक्ट अलग-अलग आईडी के साथ नहीं हो सकते।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**रिटर्न:**
int
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```


एक बाहरी ऑब्जेक्ट के लिए URL रिटर्न करता है। यह मेथड हमेशा तब बुलाया जाता है जब \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) ने [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) लौटाया हो और यह तब भी बुलाया जा सकता है जब \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) ने [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) लौटाया हो लेकिन एम्बेडिंग असंभव हो। इसे समान ऑब्जेक्ट आईडी के लिए कई बार बुलाया जा सकता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**रिटर्न:**
java.lang.String
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```


बाहरी ऑब्जेक्ट को सहेजता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |