---
title: ISwfOptions
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir sunumun SWF formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/iswfoptions/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Bir sunumun SWF formatında kaydedilmesini kontrol eden seçenekleri sağlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCompressed()](#getCompressed--) | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirtir. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirtir. |
| [getViewerIncluded()](#getViewerIncluded--) | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisinin dahil edilip edilmediğini belirtir. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisinin dahil edilip edilmediğini belirtir. |
| [getShowPageBorder()](#getShowPageBorder--) | Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirtir. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirtir. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getShowFullScreen()](#getShowFullScreen--) | Tam ekran düğmesini göster/gizle. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Tam ekran düğmesini göster/gizle. |
| [getShowPageStepper()](#getShowPageStepper--) | Sayfa adımlayıcısını göster/gizle. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Sayfa adımlayıcısını göster/gizle. |
| [getShowSearch()](#getShowSearch--) | Arama bölümünü göster/gizle. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Arama bölümünü göster/gizle. |
| [getShowTopPane()](#getShowTopPane--) | Üst bölmenin tamamını göster/gizle. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Üst bölmenin tamamını göster/gizle. |
| [getShowBottomPane()](#getShowBottomPane--) | Alt bölmeyi göster/gizle. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Alt bölmeyi göster/gizle. |
| [getShowLeftPane()](#getShowLeftPane--) | Sol bölmeyi göster/gizle. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Sol bölmeyi göster/gizle. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Açık sol panelle başla. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Açık sol panelle başla. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Bağlam menüsünü etkinleştir/devre dışı bırak. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Bağlam menüsünü etkinleştir/devre dışı bırak. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek resim. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek resim. |
| [getLogoLink()](#getLogoLink--) | Bir logo için tam hiperlink adresini alır veya ayarlar. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Bir logo için tam hiperlink adresini alır veya ayarlar. |
| [getJpegQuality()](#getJpegQuality--) | JPEG görüntülerinin kalitesini belirtir. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG görüntülerinin kalitesini belirtir. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirtir. Varsayılan true'dur.

**Döndürür:**  
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirtir. Varsayılan true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisinin dahil edilip edilmediğini belirtir. Varsayılan true'dur.

**Döndürür:**  
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisinin dahil edilip edilmediğini belirtir. Varsayılan true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirtir. Varsayılan true'dur.

**Döndürür:**  
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirtir. Varsayılan true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan false'tur.

**Döndürür:**  
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Tam ekran düğmesini göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true'dur.

**Döndürür:**  
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Tam ekran düğmesini göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Sayfa adımlayıcısını göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true'dur.

**Döndürür:**  
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Sayfa adımlayıcısını göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Arama bölümünü göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true'dur.

**Döndürür:**  
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Arama bölümünü göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Üst bölmenin tamamını göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true'dur.

**Döndürür:**  
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Üst bölmenin tamamını göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Alt bölmeyi göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true'dur.

**Döndürür:**  
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Alt bölmeyi göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Sol bölmeyi göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true'dur.

**Döndürür:**  
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Sol bölmeyi göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Açık sol panelle başla. flashvars içinde geçersiz kılınabilir. Varsayılan false'tur.

**Döndürür:**  
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Açık sol panelle başla. flashvars içinde geçersiz kılınabilir. Varsayılan false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Bağlam menüsünü etkinleştir/devre dışı bırak. Varsayılan true'dur.

**Döndürür:**  
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Bağlam menüsünü etkinleştir/devre dışı bırak. Varsayılan true'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek resim. Görüntü 32x64 piksel PNG olmalıdır, aksi takdirde logo yanlış görüntülenebilir.

**Döndürür:**  
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek resim. Görüntü 32x64 piksel PNG olmalıdır, aksi takdirde logo yanlış görüntülenebilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Bir logo için tam hiperlink adresini alır veya ayarlar. Yalnızca (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) belirtilmişse etkili olur.

**Döndürür:**  
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Bir logo için tam hiperlink adresini alır veya ayarlar. Yalnızca (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) belirtilmişse etkili olur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

JPEG görüntülerinin kalitesini belirtir. Varsayılan 95'tir.

**Döndürür:**  
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

JPEG görüntülerinin kalitesini belirtir. Varsayılan 95'tir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Bu özellik [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) türünden nesnelerin atanmasını desteklemez.

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Bu özellik [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) türünden nesnelerin atanmasını desteklemez.

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