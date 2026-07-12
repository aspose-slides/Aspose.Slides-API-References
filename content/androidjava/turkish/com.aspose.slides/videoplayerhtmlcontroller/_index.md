---
title: VideoPlayerHtmlController
second_title: Aspose.Slides for Android Java API Referansı
description: Bu sınıf video ve ses dosyalarının bir HTML'ye dışa aktarılmasını sağlar
type: docs
url: /tr/com.aspose.slides/videoplayerhtmlcontroller/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

Bu sınıf video ve ses dosyalarının bir HTML'ye dışa aktarılmasını sağlar
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | Kontrolörün yeni bir örneğini oluşturur |
## Metotlar

| Metot | Açıklama |
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


Kontrolörün yeni bir örneğini oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | java.lang.String | Video ve ses dosyalarının oluşturulacağı yol |
| fileName | java.lang.String | HTML dosyasının adı |
| baseUri | java.lang.String | Bağlantıların oluşturulması için kullanılacak temel URI |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


HTML belge başlığını yazmak için çağrılır. Sunum dönüşümü başına bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


HTML belge alt bilgisini yazmak için çağrılır. Sunum dönüşümü başına bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


HTML slayt başlığını yazmak için çağrılır. Her bir slayt için bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


HTML slayt alt bilgisini yazmak için çağrılır. Her bir slayt için bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Şeklin render edilmesinden önce çağrılır. Her bir şekil için bir kez çağrılır. Bu işlev generator'a bir şey yazar ise, mevcut slayt görüntüsü oluşturma tamamlanacak, eklenen HTML parçacığı eklenecek ve yeni görüntü öncekinin üzerine başlayacaktır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Şeklin render edilmesinden önce çağrılır. Her bir şekil için bir kez çağrılır. Bu işlev generator'a bir şey yazar ise, mevcut slayt görüntüsü oluşturma tamamlanacak, eklenen HTML parçacığı eklenecek ve yeni görüntü öncekinin üzerine başlayacaktır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```


Bu işlev, şeklin SVG'ye render edilmesinden önce çağrılarak kullanıcının sonuç SVG'yi kontrol etmesine izin verir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Nesnenin nerede saklanması gerektiğini belirler. Bu yöntem her nesne kimliği için bir kez çağrılır. Aynı veri, semanticName ve contentType ile farklı kimlikte iki nesne olabileceği garantilenmez.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**Döndürür:**
int

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```


Harici bir nesne için bir URL döndürür. Bu yöntem her zaman #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) döndürdüğünde çağrılır ve [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) döndürdüğünde gömme mümkün olmadığında da çağrılabilir. Aynı nesne kimliği için birden çok kez çağrılabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**Döndürür:**
java.lang.String

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```


Harici nesneyi kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |