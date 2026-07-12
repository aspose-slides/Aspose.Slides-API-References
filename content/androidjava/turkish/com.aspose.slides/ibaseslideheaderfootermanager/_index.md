---
title: IBaseSlideHeaderFooterManager
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Tüm slayt tipleri için altbilgi, tarih-saat ve sayfa numarası yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Tüm slayt tipleri için altbilgi, tarih-saat ve sayfa numarası yer tutucularının davranışını tutan yöneticiyi temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Altbilgi yer tutucusunun mevcut olduğunu gösteren değeri alır. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Sayfa numarası yer tutucusunun mevcut olduğunu gösteren değeri alır. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Tarih-saat yer tutucusunun mevcut olduğunu gösteren değeri alır. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Slayt altbilgi yer tutucusunun görünürlüğünü değiştirir. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Slayt sayfa numarası yer tutucusunun görünürlüğünü değiştirir. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Slayt tarih-saat yer tutucusunun görünürlüğünü değiştirir. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Slayt altbilgi yer tutucusuna metin ayarlar. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Slayt tarih-saat yer tutucusuna metin ayarlar. |

### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Altbilgi yer tutucusunun mevcut olduğunu gösteren değeri alır. Okunur boolean.

**Döndürür:**
boolean

### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Sayfa numarası yer tutucusunun mevcut olduğunu gösteren değeri alır. Okunur boolean.

**Döndürür:**
boolean

### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Tarih-saat yer tutucusunun mevcut olduğunu gösteren değeri alır. Okunur boolean.

**Döndürür:**
boolean

### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Slayt altbilgi yer tutucusunun görünürlüğünü değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - altbilgi yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Slayt sayfa numarası yer tutucusunun görünürlüğünü değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - sayfa numarası yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Slayt tarih-saat yer tutucusunun görünürlüğünü değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - tarih-saat yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Slayt altbilgi yer tutucusuna metin ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Slayt tarih-saat yer tutucusuna metin ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |