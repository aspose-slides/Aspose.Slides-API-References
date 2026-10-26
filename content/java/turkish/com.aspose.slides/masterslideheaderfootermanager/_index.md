---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides için Java API Referansı
description: Ana slayt altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm çocuk yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/masterslideheaderfootermanager/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Tüm Gerçekleştirilmiş Arabirimler:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

Ana slayt altbilgi, tarih-saat, sayfa numarası yer tutucuları ve tüm çocuk yer tutucularının davranışını tutan yöneticiyi temsil eder. Çocuk yer tutucular, bağlı düzen slaytları ve bağlı slaytlarda bulunan yer tutuculardır. Bağlı düzen slaytları ve slaytlar, ana slaytı kullanır ve ona bağımlıdır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ana slayt altbilgi yer tutucusu ve tüm çocuk altbilgi yer tutucularının görünürlüğünü değiştirir. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ana slayt sayfa numarası yer tutucusu ve tüm çocuk sayfa numarası yer tutucularının görünürlüğünü değiştirir. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ana slayt tarih-saat yer tutucusu ve tüm çocuk tarih-saat yer tutucularının görünürlüğünü değiştirir. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Metni ana slayt altbilgi yer tutucusuna ve tüm çocuk altbilgi yer tutucularına ayarlar. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Metni ana slayt tarih-saat yer tutucusuna ve tüm çocuk tarih-saat yer tutucularına ayarlar. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```


Ana slayt altbilgi yer tutucusu ve tüm çocuk altbilgi yer tutucularının görünürlüğünü değiştirir. Çocuk yer tutucular, bağlı düzen slaytları ve bağlı slaytlarda bulunan yer tutuculardır. Bağlı düzen slaytları ve slaytlar, ana slaytı kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - altbilgi yer tutucularını görünür yapar, aksi takdirde - gizler. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Ana slayt sayfa numarası yer tutucusu ve tüm çocuk sayfa numarası yer tutucularının görünürlüğünü değiştirir. Çocuk yer tutucular, bağlı düzen slaytları ve bağlı slaytlarda bulunan yer tutuculardır. Bağlı düzen slaytları ve slaytlar, ana slaytı kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - sayfa numarası yer tutucularını görünür yapar, aksi takdirde - gizler. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Ana slayt tarih-saat yer tutucusu ve tüm çocuk tarih-saat yer tutucularının görünürlüğünü değiştirir. Çocuk yer tutucular, bağlı düzen slaytları ve bağlı slaytlarda bulunan yer tutuculardır. Bağlı düzen slaytları ve slaytlar, ana slaytı kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - tarih-saat yer tutucularını görünür yapar, aksi takdirde - gizler. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```


Metni ana slayt altbilgi yer tutucusuna ve tüm çocuk altbilgi yer tutucularına ayarlar. Çocuk yer tutucular, bağlı düzen slaytları ve bağlı slaytlarda bulunan yer tutuculardır. Bağlı düzen slaytları ve slaytlar, ana slaytı kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```


Metni ana slayt tarih-saat yer tutucusuna ve tüm çocuk tarih-saat yer tutucularına ayarlar. Çocuk yer tutucular, bağlı düzen slaytları ve bağlı slaytlarda bulunan yer tutuculardır. Bağlı düzen slaytları ve slaytlar, ana slaytı kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |