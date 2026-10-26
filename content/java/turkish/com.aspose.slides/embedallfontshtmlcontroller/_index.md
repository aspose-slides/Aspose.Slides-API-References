---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides for Java API Referansı
description: Tüm sunum yazı tiplerini WOFF biçiminde gömmek için kullanılacak biçimlendirme denetleyicisi sınıfı.
type: docs
url: /tr/com.aspose.slides/embedallfontshtmlcontroller/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

Tüm sunum yazı tiplerini WOFF biçiminde gömmek için kullanılacak biçimlendirme denetleyicisi sınıfı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Yeni bir örnek oluşturur |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Yeni bir örnek oluşturur |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML belge başlığını yazmak için çağrılır. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML belge alt bilgisini yazmak için çağrılır. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML slayt başlığını yazmak için çağrılır. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML slayt alt bilgisini yazmak için çağrılır. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Şekil render edilmeden önce çağrılır. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Şekil render edilmeden önce çağrılır. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | [Presentation](../../com.aspose.slides/presentation) içinde bulunan tüm yazı tiplerini yazar. |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Verileri base64 olarak doğrudan HTML belgesine yazar. |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```


Yeni bir örnek oluşturur

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```


Yeni bir örnek oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Gömmeden hariç tutulacak yazı tipleri |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


HTML belge başlığını yazmak için çağrılır. Sunum dönüştürmesi başına bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Şu anda işlenen sunum. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


HTML belge alt bilgisini yazmak için çağrılır. Sunum dönüştürmesi başına bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Şu anda işlenen sunum. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


HTML slayt başlığını yazmak için çağrılır. Her slayt başına bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| slide | [ISlide](../../com.aspose.slides/islide) | Şu anda işlenen slayt. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


HTML slayt alt bilgisini yazmak için çağrılır. Her slayt başına bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| slide | [ISlide](../../com.aspose.slides/islide) | Şu anda işlenen slayt. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Şekil render edilmeden önce çağrılır. Her şekil için bir kez çağrılır. Bu işlev generator'a bir şey yazar ise, mevcut slayt görüntüsü oluşturma tamamlanır, ek HTML parçacığı eklenir ve yeni görüntü öncekinin üzerine başlatılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| shape | [IShape](../../com.aspose.slides/ishape) | Render edilmek üzere olan şekil. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Şekil render edilmeden önce çağrılır. Her şekil için bir kez çağrılır. Bu işlev generator'a bir şey yazar ise, mevcut slayt görüntüsü oluşturma tamamlanır, ek HTML parçacığı eklenir ve yeni görüntü öncekinin üzerine başlatılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| shape | [IShape](../../com.aspose.slides/ishape) | En son render edilen şekil. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


[Presentation](../../com.aspose.slides/presentation) içinde bulunan tüm yazı tiplerini yazar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Şu anda işlenen sunum. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```


Verileri base64 olarak doğrudan HTML belgesine yazar

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML üreticisi |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Serileştirilecek yazı tipi |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Yerine konulan yazı tipi (yazı tipi ikamesi gerçekleştiyse), aksi takdirde null |
| fontStyle | java.lang.String | Yazı tipi stili |
| fontWeight | java.lang.String | Yazı tipi kalınlığı |
| fontData | byte[] | Yazı tipi verisi |