---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides için Java API Referansı
description: Tüm tür el ilanı ve not slaytları için başlık yer tutucusunu da içeren yer tutucuların davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

Yer tutucuların davranışını tutan yöneticiyi temsil eder; tüm türler (el ilanı ve not slaytları) için başlık yer tutucusunu içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Bir başlık yer tutucusunun mevcut olduğunu gösteren değeri alır. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Slayt başlık yer tutucusunun görünürlüğünü değiştirir. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Slayt başlık yer tutucusuna metin ayarlar. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```


Bir başlık yer tutucusunun mevcut olduğunu gösteren değeri alır. Boolean okur.

**Döndürür:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```


Slayt başlık yer tutucusunun görünürlüğünü değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - bir başlık yer tutucusunu görünür yapar, aksi takdirde - gizler. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```


Slayt başlık yer tutucusuna metin ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |