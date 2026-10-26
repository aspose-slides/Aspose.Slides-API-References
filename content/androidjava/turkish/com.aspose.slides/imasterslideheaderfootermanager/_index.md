---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides for Android Java API Referansı
description: Master slayt altbilgi, tarih-zaman ve sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/imasterslideheaderfootermanager/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Master slayt altbilgi, tarih-zaman, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar master slaytı kullanır ve ona bağımlıdır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Master slayt altbilgi yer tutucusunun ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Master slayt sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Master slayt tarih-zaman yer tutucusunun ve tüm alt tarih-zaman yer tutucularının görünürlüğünü değiştirir. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Metni master slayt altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına ayarlar. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Metni master slayt tarih-zaman yer tutucusuna ve tüm alt tarih-zaman yer tutucularına ayarlar. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Master slayt altbilgi yer tutucusunun ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar master slaytı kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - altbilgi yer tutucularını görünür yapar, aksi takdirde gizler. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Master slayt sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar master slaytı kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - sayfa numarası yer tutucularını görünür yapar, aksi takdirde gizler. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Master slayt tarih-zaman yer tutucusunun ve tüm alt tarih-zaman yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar master slaytı kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - tarih-zaman yer tutucularını görünür yapar, aksi takdirde gizler. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Metni master slayt altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına ayarlar. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar master slaytı kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Metni master slayt tarih-zaman yer tutucusuna ve tüm alt tarih-zaman yer tutucularına ayarlar. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar master slaytı kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |