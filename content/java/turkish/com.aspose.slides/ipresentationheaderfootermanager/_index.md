---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides for Java API Referansı
description: Sunumdaki tüm altbilgi, tarih-saat ve sayfa numarası yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/ipresentationheaderfootermanager/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Sunumun tüm altbilgi, tarih-saat ve sayfa numarası yer tutucularının davranışını tutan yöneticiyi temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Tüm başlık yer tutucularının görünürlüğünü değiştirir, notlar ana şablonu, not slaytları ve el ilanı ana şablonu dahil. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Tüm altbilgi yer tutucularının görünürlüğünü değiştirir, ana slaytlar, düzen slaytları ve slaytlar dahil. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Tüm sayfa numarası yer tutucularının görünürlüğünü değiştirir, ana slaytlar, düzen slaytları ve slaytlar dahil. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Tüm tarih-saat yer tutucularının görünürlüğünü değiştirir, ana slaytlar, düzen slaytları ve slaytlar dahil. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Tüm başlık yer tutucularına metin ayarlar, notlar ana şablonu, not slaytları ve el ilanı ana şablonu dahil. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Tüm altbilgi yer tutucularına metin ayarlar, ana slaytlar, düzen slaytları ve slaytlar dahil. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Tüm tarih-saat yer tutucularına metin ayarlar, ana slaytlar, düzen slaytları ve slaytlar dahil. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Tüm başlık slaytları ve ilk düzen slaytı için altbilgi, tarih-saat ve sayfa numarası yer tutucularının görünürlüğünü değiştirir. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Tüm başlık yer tutucularının görünürlüğünü değiştirir, notlar ana şablonu, not slaytları ve el ilanı ana şablonu dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - bir başlık yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Tüm altbilgi yer tutucularının görünürlüğünü değiştirir, ana slaytlar, düzen slaytları ve slaytlar dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - bir altbilgi yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Tüm sayfa numarası yer tutucularının görünürlüğünü değiştirir, ana slaytlar, düzen slaytları ve slaytlar dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - bir sayfa numarası yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Tüm tarih-saat yer tutucularının görünürlüğünü değiştirir, ana slaytlar, düzen slaytları ve slaytlar dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - bir tarih-saat yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Tüm başlık yer tutucularına metin ayarlar, notlar ana şablonu, not slaytları ve el ilanı ana şablonu dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Tüm altbilgi yer tutucularına metin ayarlar, ana slaytlar, düzen slaytları ve slaytlar dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Tüm tarih-saat yer tutucularına metin ayarlar, ana slaytlar, düzen slaytları ve slaytlar dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Başlık slaytları – ilk düzen slaytına dayalı slaytlar (bu ilk düzenin tipinden bağımsız) için altbilgi, tarih-saat ve sayfa numarası yer tutucularının görünürlüğünü değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - yer tutucuları görünür yapar, aksi takdirde gizler. |