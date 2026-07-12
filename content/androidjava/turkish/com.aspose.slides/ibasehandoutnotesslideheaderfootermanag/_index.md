---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides Android için Java API Referansı
description: Tüm tiplerde el dağıtımı ve not slaytları için başlık yer tutucusunu içeren, yer tutucuların davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Yer tutucuların davranışını tutan yöneticiyi temsil eder, tüm tiplerde el dağıtımı ve not slaytları için başlık yer tutucusunu içerir.

--------------------

Orijinal arabirim adı "IBaseHandoutNotesSlideHeaderFooterManager" COM uyumluluğu için "IBaseHandoutNotesSlideHeaderFooterManag" olarak kısaltıldı (tip adı uzunluğu 39 karakteri geçmemelidir).
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Bir başlık yer tutucusunun var olduğunu gösteren değeri alır. Boolean okur. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Slayt başlık yer tutucusunun görünürlüğünü değiştirir. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Başlık yer tutucusuna metin ayarlar. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Bir başlık yer tutucusunun var olduğunu gösteren değeri alır. Boolean okur.

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


Başlık yer tutucusuna metin ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |