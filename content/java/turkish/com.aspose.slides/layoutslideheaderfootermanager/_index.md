---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides for Java API Referansı
description: Düzen slaytının altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/layoutslideheaderfootermanager/
---
**Kalıtım:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Uygulanan Tüm Arabirimler:**  
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)  
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Düzen slaytının altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar, düzen slaytını kullanır ve ona bağımlıdır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Düzen slaytının altbilgi yer tutucusunun ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Düzen slaytının sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Düzen slaytının tarih-saat yer tutucusunun ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Düzen slaytının altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına metin ayarlar. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Düzen slaytının tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına metin ayarlar. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Düzen slaytının altbilgi yer tutucusunun ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar, ana slaytı kullanır ve ona bağımlıdır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - altbilgi yer tutucularını görünür yapar, aksi takdirde gizler. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Düzen slaytının sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar, düzen slaytını kullanır ve ona bağımlıdır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - sayfa numarası yer tutucularını görünür yapar, aksi takdirde gizler. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Düzen slaytının tarih-saat yer tutucusunun ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar, düzen slaytını kullanır ve ona bağımlıdır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - tarih-saat yer tutucularını görünür yapar, aksi takdirde gizler. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Düzen slaytının altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar, düzen slaytını kullanır ve ona bağımlıdır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Düzen slaytının tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar, düzen slaytını kullanır ve ona bağımlıdır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |