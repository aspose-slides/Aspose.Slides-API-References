---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides Java API referencia
description: A menedzsert képviseli, amely a helyőrzők működését kezeli, beleértve a fejléchelyőrzőt minden típusú kiosztó- és jegyzetdia esetén.
type: docs
url: /hu/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Minden megvalósított interfész:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

A menedzsert képviseli, amely a helyőrzők működését kezeli, beleértve a fejléchelyőrzőt minden típusú kiosztó és jegyzet dia esetén.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Értéket ad vissza, amely jelzi, hogy egy fejléchelyőrző jelen van. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Megváltoztatja a dia fejléchelyőrző láthatóságát. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Szöveget állít be a dia fejléchelyőrzőhöz. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```


Értéket ad vissza, amely jelzi, hogy egy fejléchelyőrző jelen van. Olvas boolean.

**Visszatér:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```


Megváltoztatja a dia fejléchelyőrző láthatóságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá tesz egy fejléchelyőrzőt, egyébként – elrejti azt. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```


Szöveget állít be a dia fejléchelyőrzőhöz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |