---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides Java API Referansı
description: Tüm slayt türleri için altbilgi, tarih-zaman ve sayfa numarası yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Altbilgi, tarih-zaman ve sayfa numarası yer tutucularının davranışını tutan bir yöneticiyi temsil eder ve tüm slayt türleri için geçerlidir.

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Altbilgi yer tutucusunun mevcut olduğunu gösteren değeri alır. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Sayfa numarası yer tutucusunun mevcut olduğunu gösteren değeri alır. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Tarih-zaman yer tutucusunun mevcut olduğunu gösteren değeri alır. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Slayt altbilgi yer tutucusunun görünürlüğünü değiştirir. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Slayt sayfa numarası yer tutucusunun görünürlüğünü değiştirir. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Slayt tarih-zaman yer tutucusunun görünürlüğünü değiştirir. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Slayt altbilgi yer tutucusuna metin ayarlar. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Slayt tarih-zaman yer tutucusuna metin ayarlar. |

### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Altbilgi yer tutucusunun mevcut olduğunu gösteren değeri alır. Boolean okur.

**Döndürür:**
boolean

### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Sayfa numarası yer tutucusunun mevcut olduğunu gösteren değeri alır. Boolean okur.

**Döndürür:**
boolean

### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Tarih-zaman yer tutucusunun mevcut olduğunu gösteren değeri alır. Boolean okur.

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
| isVisible | boolean | true - bir altbilgi yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Slayt sayfa numarası yer tutucusunun görünürlüğünü değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - bir sayfa numarası yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Slayt tarih-zaman yer tutucusunun görünürlüğünü değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - bir tarih-zaman yer tutucusunu görünür yapar, aksi takdirde gizler. |

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

Slayt tarih-zaman yer tutucusuna metin ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |