---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Android via Java API Referansı
description: Tüm tip el ilanı ve not slaytları için başlık yer tutucusu dahil olmak üzere yer tutucuların davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

Tüm tip el ilanı ve not slaytları için başlık yer tutucusu dahil olmak üzere yer tutucuların davranışını tutan yöneticiyi temsil eder.
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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - bir başlık yer tutucusunu görünür yapar, aksi takdirde gizler. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```

Slayt başlık yer tutucusuna metin ayarlar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |