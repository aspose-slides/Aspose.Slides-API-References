---
title: BaseSlideHeaderFooterManager
second_title: Aspose.Slides Java API hivatkozás
description: Egy menedzsert képvisel, amely kezeli a lábléc, dátum-idő és oldalszám helyőrzők viselkedését minden diatípus esetén.
type: docs
url: /hu/com.aspose.slides/baseslideheaderfootermanager/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

A menedzser képviseli, amely kezeli az összes diatípus lábléc, dátum-idő és oldalszám helyőrzőinek viselkedését.
## Módszerek

| Method | Description |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Értéket kap, amely jelzi, hogy a lábléc helyőrző jelen van. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Értéket kap, amely jelzi, hogy az oldalszám helyőrző jelen van. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Értéket kap, amely jelzi, hogy a dátum-idő helyőrző jelen van. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Megváltoztatja a dia lábléc helyőrző láthatóságát. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Megváltoztatja a dia oldalszám helyőrző láthatóságát. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Megváltoztatja a dia dátum-idő helyőrző láthatóságát. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Szöveget állít be a dia lábléc helyőrzőjéhez. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Szöveget állít be a dia dátum-idő helyőrzőjéhez. |
### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

Értéket kap, amely jelzi, hogy a lábléc helyőrző jelen van. Olvasható boolean.

**Visszatérési érték:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

Értéket kap, amely jelzi, hogy az oldalszám helyőrző jelen van. Olvasható boolean.

**Visszatérési érték:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

Értéket kap, amely jelzi, hogy a dátum-idő helyőrző jelen van. Olvasható boolean.

**Visszatérési érték:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

Megváltoztatja a dia lábléc helyőrző láthatóságát.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true – lábléc helyőrzőt láthatóvá teszi, egyébként elrejti. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

Megváltoztatja a dia oldalszám helyőrző láthatóságát.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true – oldalszám helyőrzőt láthatóvá teszi, egyébként elrejti. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

Megváltoztatja a dia dátum-idő helyőrző láthatóságát.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true – dátum-idő helyőrzőt láthatóvá teszi, egyébként elrejti. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

Szöveget állít be a dia lábléc helyőrzőjébe.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

Szöveget állít be a dia dátum-idő helyőrzőjébe.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |