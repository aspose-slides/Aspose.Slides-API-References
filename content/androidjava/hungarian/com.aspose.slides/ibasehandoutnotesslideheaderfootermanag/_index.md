---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides Androidhoz a Java API hivatkozás
description: Kezelőt reprezentál, amely a helyőrzők viselkedését tartalmazza, beleértve a fejléchelyőrzőt minden típusú handout és notes dián.
type: docs
url: /hu/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

A menedzsert reprezentálja, amely a helyőrzők viselkedését kezeli, beleértve a fejléchelyőrzőt minden típusú handout és notes dia esetén.

--------------------

Az eredeti interfész neve "IBaseHandoutNotesSlideHeaderFooterManager" le lett csonkítva "IBaseHandoutNotesSlideHeaderFooterManag"-ra a COM kompatibilitás miatt (a típusnév hossza legfeljebb 39 karakter lehet).
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Gets value indicating that a header placeholder is present. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Changes slide header placeholder visibility. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Sets text to slide header placeholder. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

Olvasható boolean.

**Visszatérési érték:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

Changes slide header placeholder visibility.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a fejléchelyőrzőt, egyébként - elrejti. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

Sets text to slide header placeholder.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Text to set. |