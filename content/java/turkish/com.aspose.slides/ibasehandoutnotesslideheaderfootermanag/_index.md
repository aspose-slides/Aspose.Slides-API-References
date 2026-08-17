---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides Java API Referansı
description: Tüm tipte el kitabı ve not slaytları için başlık yer tutucusu dahil, yer tutucuların davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Tüm türde el kitabı ve not slaytları için başlık yer tutucusu dahil, yer tutucuların davranışını tutan yöneticiyi temsil eder.

--------------------

Orijinal arayüz adı "IBaseHandoutNotesSlideHeaderFooterManager" COM uyumluluğu için "IBaseHandoutNotesSlideHeaderFooterManag" olarak kısaltılmıştır (tür adı uzunluğu 39 karakteri geçmemelidir).

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Başlık yer tutucusunun mevcut olduğunu gösteren değeri alır. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Slayt başlık yer tutucusunun görünürlüğünü değiştirir. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Slayt başlık yer tutucusuna metin ayarlar. |

### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

Başlık yer tutucusunun mevcut olduğunu gösteren değeri alır. Boolean okur.

**Döndürür:**
boolean

### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

Slayt başlık yer tutucusunun görünürlüğünü değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - bir başlık yer tutucusunu görünür yapar, aksi takdirde - gizler. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

Slayt başlık yer tutucusuna metin ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |