---
title: SwfOptions
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir sunumun Swf formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.
type: docs
url: /tr/com.aspose.slides/swfoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Bir sunumun Swf formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Bir sunum dosyasını temsil eden Presentation nesnesini örnekleyin
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Sunumu ve not sayfalarını kaydediyor
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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getCompressed()](#getCompressed--) | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirtir. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirtir. |
| [getViewerIncluded()](#getViewerIncluded--) | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisini içerip içermeyeceğini belirtir. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisini içerip içermeyeceğini belirtir. |
| [getShowPageBorder()](#getShowPageBorder--) | Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirtir. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirtir. |
| [getShowFullScreen()](#getShowFullScreen--) | Tam ekran düğmesini göster/gizle. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Tam ekran düğmesini göster/gizle. |
| [getShowPageStepper()](#getShowPageStepper--) | Sayfa adımcısını göster/gizle. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Sayfa adımcısını göster/gizle. |
| [getShowSearch()](#getShowSearch--) | Arama bölümünü göster/gizle. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Arama bölümünü göster/gizle. |
| [getShowTopPane()](#getShowTopPane--) | Tüm üst bölmeyi göster/gizle. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Tüm üst bölmeyi göster/gizle. |
| [getShowBottomPane()](#getShowBottomPane--) | Alt bölmeyi göster/gizle. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Alt bölmeyi göster/gizle. |
| [getShowLeftPane()](#getShowLeftPane--) | Sol bölmeyi göster/gizle. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Sol bölmeyi göster/gizle. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Açık sol bölmeyle başla. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Açık sol bölmeyle başla. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Bağlam menüsünü etkinleştir/devre dışı bırak. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Bağlam menüsünü etkinleştir/devre dışı bırak. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek görüntü. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek görüntü. |
| [getLogoLink()](#getLogoLink--) | Bir logo için tam hiperlink adresini alır veya ayarlar. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Bir logo için tam hiperlink adresini alır veya ayarlar. |
| [getJpegQuality()](#getJpegQuality--) | JPEG görüntülerinin kalitesini belirtir. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG görüntülerinin kalitesini belirtir. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Bir sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Bir sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Varsayılan yapıcı.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan değer false'tur.

**Döndürür:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan değer false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirtir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirtir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisini içerip içermeyeceğini belirtir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisini içerip içermeyeceğini belirtir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirtir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirtir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

Tam ekran düğmesini göster/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

Tam ekran düğmesini göster/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

Sayfa adımcısını göster/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

Sayfa adımcısını göster/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Arama bölümünü göster/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

Arama bölümünü göster/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

Tüm üst bölmeyi göster/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Tüm üst bölmeyi göster/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Alt bölmeyi göster/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Alt bölmeyi göster/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Sol bölmeyi göster/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Sol bölmeyi göster/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Açık sol bölmeyle başlar. flashvars içinde geçersiz kılınabilir. Varsayılan değer false'tur.

**Döndürür:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Açık sol bölmeyle başlar. flashvars içinde geçersiz kılınabilir. Varsayılan değer false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

Bağlam menüsünü etkinleştirir/devre dışı bırakır. Varsayılan değer true'dur.

**Döndürür:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

Bağlam menüsünü etkinleştirir/devre dışı bırakır. Varsayılan değer true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek görüntü. Görüntü 32x64 piksel PNG olmalıdır, aksi takdirde logo düzgün görüntülenmeyebilir.

**Döndürür:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek görüntü. Görüntü 32x64 piksel PNG olmalıdır, aksi takdirde logo düzgün görüntülenmeyebilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

Bir logo için tam hiperlink adresini alır veya ayarlar. Yalnızca bir (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) belirtildiğinde etkili olur.

**Döndürür:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Bir logo için tam hiperlink adresini alır veya ayarlar. Yalnızca bir (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) belirtildiğinde etkili olur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

JPEG görüntülerinin kalitesini belirtir. Varsayılan değer 95'tir.

**Döndürür:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

JPEG görüntülerinin kalitesini belirtir. Varsayılan değer 95'tir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Bir sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Bu özellik [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) türündeki nesnelerin atanmasını desteklemez.

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

Bir sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Bu özellik [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) türündeki nesnelerin atanmasını desteklemez.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |