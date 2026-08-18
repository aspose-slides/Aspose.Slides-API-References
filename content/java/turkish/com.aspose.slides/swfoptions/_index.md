---
title: SwfOptions
second_title: Aspose.Slides için Java API Referansı
description: Sunumun Swf formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/swfoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Sunumun Swf formatında kaydedilmesini kontrol eden seçenekleri sağlar.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Bir sunum dosyasını temsil eden Presentation nesnesini başlat.
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Sunumu ve not sayfalarını kaydetme
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Varsayılan yapıcı. |
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. |
| [getCompressed()](#getCompressed--) | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirler. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirler. |
| [getViewerIncluded()](#getViewerIncluded--) | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisini içerip içermeyeceğini belirler. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisini içerip içermeyeceğini belirler. |
| [getShowPageBorder()](#getShowPageBorder--) | Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirler. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirler. |
| [getShowFullScreen()](#getShowFullScreen--) | Tam ekran düğmesini göster/gizle. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Tam ekran düğmesini göster/gizle. |
| [getShowPageStepper()](#getShowPageStepper--) | Sayfa adımlayıcısını göster/gizle. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Sayfa adımlayıcısını göster/gizle. |
| [getShowSearch()](#getShowSearch--) | Arama bölümünü göster/gizle. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Arama bölümünü göster/gizle. |
| [getShowTopPane()](#getShowTopPane--) | Üst panelin tamamını göster/gizle. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Üst panelin tamamını göster/gizle. |
| [getShowBottomPane()](#getShowBottomPane--) | Alt paneli göster/gizle. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Alt paneli göster/gizle. |
| [getShowLeftPane()](#getShowLeftPane--) | Sol paneli göster/gizle. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Sol paneli göster/gizle. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Açık sol panel ile başla. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Açık sol panel ile başla. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Bağlam menüsünü etkinleştir/devre dışı bırak. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Bağlam menüsünü etkinleştir/devre dışı bırak. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Görüntüleyicinin sağ üst köşesinde logo olarak görüntülenecek resim. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Görüntüleyicinin sağ üst köşesinde logo olarak görüntülenecek resim. |
| [getLogoLink()](#getLogoLink--) | Bir logo için tam hiperlink adresini alır veya ayarlar. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Bir logo için tam hiperlink adresini alır veya ayarlar. |
| [getJpegQuality()](#getJpegQuality--) | JPEG görüntülerinin kalitesini belirler. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG görüntülerinin kalitesini belirler. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunum dışa aktarılırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunum dışa aktarılırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Varsayılan yapıcı.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan değer false'tur.

**Döndürür:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan değer false'tur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirler. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirler. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisini içerip içermeyeceğini belirler. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisini içerip içermeyeceğini belirler. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirler. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirler. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

Tam ekran düğmesini göster/gizle. Flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

Tam ekran düğmesini göster/gizle. Flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

Sayfa adımlayıcısını göster/gizle. Flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

Sayfa adımlayıcısını göster/gizle. Flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Arama bölümünü göster/gizle. Flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

Arama bölümünü göster/gizle. Flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

Üst panelin tamamını göster/gizle. Flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Üst panelin tamamını göster/gizle. Flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Alt paneli göster/gizle. Flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Alt paneli göster/gizle. Flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Sol paneli göster/gizle. Flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Sol paneli göster/gizle. Flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Açık sol panel ile başla. Flashvars içinde geçersiz kılınabilir. Varsayılan değer false'tur.

**Döndürür:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Açık sol panel ile başla. Flashvars içinde geçersiz kılınabilir. Varsayılan değer false'tur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

Bağlam menüsünü etkinleştir/devre dışı bırak. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

Bağlam menüsünü etkinleştir/devre dışı bırak. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

Görüntüleyicinin sağ üst köşesinde logo olarak görüntülenecek resim. Resim 32x64 piksel PNG olmalıdır, aksi takdirde logo hatalı görüntülenebilir.

**Döndürür:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Görüntüleyicinin sağ üst köşesinde logo olarak görüntülenecek resim. Resim 32x64 piksel PNG olmalıdır, aksi takdirde logo hatalı görüntülenebilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

Bir logo için tam hiperlink adresini alır veya ayarlar. Yalnızca (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) belirtilmişse etkili olur.

**Döndürür:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Bir logo için tam hiperlink adresini alır veya ayarlar. Yalnızca (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) belirtilmişse etkili olur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

JPEG görüntülerinin kalitesini belirler. Varsayılan değer 95'tir.

**Döndürür:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

JPEG görüntülerinin kalitesini belirler. Varsayılan değer 95'tir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Sunum dışa aktarılırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Bu özellik [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) tipinde nesnelerin atanmasını desteklemez.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Sunum dışa aktarılırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Bu özellik [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) tipinde nesnelerin atanmasını desteklemez.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |