---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides için Java API Referansı
description: Ana slayt altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/imasterslideheaderfootermanager/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Ana slayt altbilgi, tarih-saat ve sayfa numarası yer tutucularının davranışını ve tüm alt yer tutucuları tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlar üzerinde bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar, ana slaytı kullanır ve ona bağlıdır.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ana slayt altbilgi yer tutucusunun ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ana slayt sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ana slayt tarih-saat yer tutucusunun ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ana slayt altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına metin ayarlar. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ana slayt tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına metin ayarlar. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ana slayt altbilgi yer tutucusunun ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlar üzerinde bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar, ana slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - altbilgi yer tutucularını görünür yapar, aksi takdirde gizler. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ana slayt sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlar üzerinde bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar, ana slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - sayfa numarası yer tutucularını görünür yapar, aksi takdirde gizler. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ana slayt tarih-saat yer tutucusunun ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlar üzerinde bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar, ana slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - tarih-saat yer tutucularını görünür yapar, aksi takdirde gizler. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ana slayt altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlar üzerinde bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar, ana slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ana slayt tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlar üzerinde bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar, ana slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |