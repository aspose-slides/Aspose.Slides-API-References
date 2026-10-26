---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controls a html file generation.
type: docs
url: /tr/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

HTML dosyası oluşturulmasını kontrol eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML belge başlığını yazmak için çağrılır. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML belge alt bilgisini yazmak için çağrılır. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML slayt başlığını yazmak için çağrılır. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML slayt alt bilgisini yazmak için çağrılır. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Şeklin render edilmesinden önce çağrılır. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Şeklin render edilmesinden önce çağrılır. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


HTML belge başlığını yazmak için çağrılır. Sunum dönüşümü başına bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Şu anda işlenen sunum. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


HTML belge alt bilgisini yazmak için çağrılır. Sunum dönüşümü başına bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Şu anda işlenen sunum. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


HTML slayt başlığını yazmak için çağrılır. Her slayt için bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| slide | [ISlide](../../com.aspose.slides/islide) | Şu anda işlenen slayt. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


HTML slayt alt bilgisini yazmak için çağrılır. Her slayt için bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| slide | [ISlide](../../com.aspose.slides/islide) | Şu anda işlenen slayt. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Şeklin render edilmesinden önce çağrılır. Her şekil için bir kez çağrılır. Bu işlev generator'a bir şey yazarsa, geçerli slayt görüntüsü oluşturma tamamlanacak, eklenen html parçacığı eklenecek ve yeni görüntü öncekinin üzerine başlayacaktır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| shape | [IShape](../../com.aspose.slides/ishape) | Render edilmek üzere olan şekil. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Şeklin render edilmesinden önce çağrılır. Her şekil için bir kez çağrılır. Bu işlev generator'a bir şey yazarsa, geçerli slayt görüntüsü oluşturma tamamlanacak, eklenen html parçacığı eklenecek ve yeni görüntü öncekinin üzerine başlayacaktır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| shape | [IShape](../../com.aspose.slides/ishape) | Son render edilen şekil. |