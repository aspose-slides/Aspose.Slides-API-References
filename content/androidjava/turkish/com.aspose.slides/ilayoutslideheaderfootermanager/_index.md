---
title: ILayoutSlideHeaderFooterManager
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Düzen slayt altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Düzen slayt altbilgi, tarih-saat ve sayfa numarası yer tutucularının davranışını ve tüm alt yer tutucuları yöneten bir yöneticiyi temsil eder. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutuculardır. Bağımlı slaytlar, düzen slaytını kullanır ve ona bağımlıdır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Düzen slayt altbilgi yer tutucusunun ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Düzen slayt sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Düzen slayt tarih-saat yer tutucusunun ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Düzen slayt altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına metin ayarlar. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Düzen slayt tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına metin ayarlar. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Düzen slayt altbilgi yer tutucusunun ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutuculardır. Bağımlı slaytlar, ana slaytı kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true – altbilgi yer tutucularını görünür kılar, aksi takdirde gizler. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Düzen slayt sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutuculardır. Bağımlı slaytlar, düzen slaytını kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true – sayfa numarası yer tutucularını görünür kılar, aksi takdirde gizler. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Düzen slayt tarih-saat yer tutucusunun ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutuculardır. Bağımlı slaytlar, düzen slaytını kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true – tarih-saat yer tutucularını görünür kılar, aksi takdirde gizler. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Düzen slayt altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutuculardır. Bağımlı slaytlar, düzen slaytını kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Düzen slayt tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutuculardır. Bağımlı slaytlar, düzen slaytını kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |