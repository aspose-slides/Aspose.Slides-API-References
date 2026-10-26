---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides Android için Java API Referansı
description: Düzen slaytının altbilgi, tarih-saat, sayfa numarası yer tutucuları ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/layoutslideheaderfootermanager/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Düzen slayt altbilgi, tarih-saat, sayfa numarası yer tutucuları ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar, düzen slaytı kullanır ve ona bağlıdır.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Düzen slayt altbilgi yer tutucusu ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Düzen slayt sayfa numarası yer tutucusu ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Düzen slayt tarih-saat yer tutucusu ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Metni düzen slayt altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına ayarlar. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Metni düzen slayt tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına ayarlar. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Düzen slayt altbilgi yer tutucusu ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar, ana slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - bir altbilgi yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Düzen slayt sayfa numarası yer tutucusu ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar, düzen slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - bir sayfa numarası yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Düzen slayt tarih-saat yer tutucusu ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar, düzen slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - bir tarih-saat yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Metni düzen slayt altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına ayarlar. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar, düzen slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Metni düzen slayt tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına ayarlar. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar, düzen slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |