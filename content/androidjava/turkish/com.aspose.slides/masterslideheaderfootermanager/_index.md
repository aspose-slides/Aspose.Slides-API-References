---
title: MasterSlideHeaderFooterManager
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Ana slayt altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/masterslideheaderfootermanager/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

Ana slayt altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı yerleşim slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı yerleşim slaytları ve slaytlar, ana slaytı kullanır ve ona bağlıdır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ana slayt altbilgi yer tutucusunu ve tüm alt yer tutucu altbilgileri görünürlük durumunu değiştirir. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ana slayt sayfa numarası yer tutucusunu ve tüm alt yer tutucu sayfa numaralarını görünürlük durumunu değiştirir. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ana slayt tarih-saat yer tutucusunu ve tüm alt yer tutucu tarih-saatleri görünürlük durumunu değiştirir. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ana slayt altbilgi yer tutucusuna ve tüm alt yer tutucu altbilgilere metin ayarlar. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ana slayt tarih-saat yer tutucusuna ve tüm alt yer tutucu tarih-saatlerine metin ayarlar. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ana slayt altbilgi yer tutucusunu ve tüm alt yer tutucu altbilgileri görünürlük durumunu değiştirir. Alt yer tutucular, bağımlı yerleşim slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı yerleşim slaytları ve slaytlar, ana slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - altbilgi yer tutucularını görünür kılar, aksi takdirde gizler. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ana slayt sayfa numarası yer tutucusunu ve tüm alt yer tutucu sayfa numaralarını görünürlük durumunu değiştirir. Alt yer tutucular, bağımlı yerleşim slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı yerleşim slaytları ve slaytlar, ana slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - sayfa numarası yer tutucularını görünür kılar, aksi takdirde gizler. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ana slayt tarih-saat yer tutucusunu ve tüm alt yer tutucu tarih-saatleri görünürlük durumunu değiştirir. Alt yer tutucular, bağımlı yerleşim slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı yerleşim slaytları ve slaytlar, ana slaytı kullanır ve ona bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - tarih-saat yer tutucularını görünür kılar, aksi takdirde gizler. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Ana slayt altbilgi yer tutucusuna ve tüm alt yer tutucu altbilgilere metin ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Ana slayt tarih-saat yer tutucusuna ve tüm alt yer tutucu tarih-saatlerine metin ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |