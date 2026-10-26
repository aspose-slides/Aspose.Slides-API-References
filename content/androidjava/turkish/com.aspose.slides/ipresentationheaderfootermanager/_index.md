---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides for Android Java API Referansı
description: Sunumdaki tüm alt bilgi, tarih-saat ve sayfa numarası yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/ipresentationheaderfootermanager/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Sunumun tüm alt bilgi, tarih-saat ve sayfa numarası yer tutucularının davranışını tutan yöneticiyi temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Changes all header placeholders visibility, including notes master, notes slides and handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Changes all footer placeholders visibility, including master slides, layout slides and slides. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Changes all page number placeholders visibility, including master slides, layout slides and slides. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Changes all date-time placeholders visibility, including master slides, layout slides and slides. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Sets text to all header placeholders, including notes master, notes slides and handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Sets text to all footer placeholders, including master slides, layout slides and slides. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Sets text to all date-time placeholders, including master slides, layout slides and slides. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Changes the footer, date-time and page number placeholders visibility for all title slides and for first layout slide. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```


Tüm başlık yer tutucularının görünürlüğünü değiştirir, notlar ana sayfası, not slaytları ve el ilanı ana sayfası dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - başlık yer tutucularını görünür kılar, aksi takdirde - gizler. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```


Tüm alt bilgi yer tutucularının görünürlüğünü değiştirir, ana slaytlar, yerleşim slaytları ve slaytlar dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - alt bilgi yer tutucularını görünür kılar, aksi takdirde - gizler. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```


Tüm sayfa numarası yer tutucularının görünürlüğünü değiştirir, ana slaytlar, yerleşim slaytları ve slaytlar dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - sayfa numarası yer tutucularını görünür kılar, aksi takdirde - gizler. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```


Tüm tarih-saat yer tutucularının görünürlüğünü değiştirir, ana slaytlar, yerleşim slaytları ve slaytlar dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - tarih-saat yer tutucularını görünür kılar, aksi takdirde - gizler. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```


Tüm başlık yer tutucularına metin atar, notlar ana sayfası, not slaytları ve el ilanı ana sayfası dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```


Tüm alt bilgi yer tutucularına metin atar, ana slaytlar, yerleşim slaytları ve slaytlar dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```


Tüm tarih-saat yer tutucularına metin atar, ana slaytlar, yerleşim slaytları ve slaytlar dahil.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```


Tüm başlık slaytları ve ilk yerleşim slaytı için alt bilgi, tarih-saat ve sayfa numarası yer tutucularının görünürlüğünü değiştirir. Title slides – ilk yerleşim slaytına dayalı slaytlar (bu ilk yerleşimin türü ne olursa olsun).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - yer tutucuları görünür kılar, aksi takdirde - gizler. |