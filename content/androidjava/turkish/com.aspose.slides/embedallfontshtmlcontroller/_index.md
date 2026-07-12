---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides Android için Java API Referansı
description: WOFF formatında tüm sunum yazı tiplerini gömmek için kullanılacak biçimlendirme denetleyici sınıfı.
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

Tüm sunum yazı tiplerini WOFF biçiminde gömmek için kullanılacak biçimlendirme denetleyici sınıfı.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Yeni bir örnek oluşturur |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Yeni bir örnek oluşturur |

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML belge başlığını yazmak için çağrılır. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML belge alt bilgisini yazmak için çağrılır. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML slayt başlığını yazmak için çağrılır. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML slayt alt bilgisini yazmak için çağrılır. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Şekil oluşturulmadan önce çağrılır. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Şekil oluşturulmadan önce çağrılır. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Tüm yazı tiplerini [Presentation](../../com.aspose.slides/presentation) içinde yazar. |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Verileri base64 olarak HTML belgesine yazar. |

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
| fontNameExcludeList | java.lang.String[] | Gömme dışındakı bırakılacak yazı tipleri |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTML belge başlığını yazmak için çağrılır. Sunum dönüşümü başına bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Şu anda oluşturulan sunum. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTML belge alt bilgisini yazmak için çağrılır. Sunum dönüşümü başına bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Şu anda oluşturulan sunum. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTML slayt başlığını yazmak için çağrılır. Her slayt başına bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| slide | [ISlide](../../com.aspose.slides/islide) | Şu anda oluşturulan slayt. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTML slayt alt bilgisini yazmak için çağrılır. Her slayt başına bir kez çağrılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| slide | [ISlide](../../com.aspose.slides/islide) | Şu anda oluşturulan slayt. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Şekil oluşturulmadan önce çağrılır. Her şekil başına bir kez çağrılır. Bu işlev generator’a bir şey yazarsa, mevcut slayt görüntüsü oluşturulması tamamlanır, ek HTML parçacığı eklenir ve yeni görüntü öncekinin üzerine başlatılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| shape | [IShape](../../com.aspose.slides/ishape) | Oluşturulmak üzere olan şekil. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Şekil oluşturulmadan önce çağrılır. Her şekil başına bir kez çağrılır. Bu işlev generator’a bir şey yazarsa, mevcut slayt görüntüsü oluşturulması tamamlanır, ek HTML parçacığı eklenir ve yeni görüntü öncekinin üzerine başlatılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| shape | [IShape](../../com.aspose.slides/ishape) | Son oluşturulan şekil. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

[Presentation](../../com.aspose.slides/presentation) içinde bulunan tüm yazı tiplerini yazar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Çıktı nesnesi. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Şu anda oluşturulan sunum. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

Verileri base64 olarak HTML belgesine yazar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML generator |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Serileştirilecek yazı tipi |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Değiştirilen yazı tipi (yazı tipi değişimi gerçekleşmişse), aksi takdirde null |
| fontStyle | java.lang.String | Yazı tipi stili |
| fontWeight | java.lang.String | Yazı tipi kalınlığı |
| fontData | byte[] | Yazı tipi verisi |