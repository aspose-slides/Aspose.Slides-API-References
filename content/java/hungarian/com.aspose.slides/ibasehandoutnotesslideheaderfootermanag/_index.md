---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides Java API hivatkozás
description: Kezelőt képvisel, amely a helyőrzők viselkedését tartalmazza, beleértve a fejléc helyőrzőt minden típusú anyag- és jegyzetdia esetén.
type: docs
url: /hu/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Kezelőt képvisel, amely a helyőrzők viselkedését tartalmazza, beleértve a fejléc helyőrzőt minden típusú anyag- és jegyzetdia esetén.

--------------------

Az eredeti interfész neve „IBaseHandoutNotesSlideHeaderFooterManager” le lett rövidítve „IBaseHandoutNotesSlideHeaderFooterManag” névre a COM kompatibilitás érdekében (a típusnév hossza legfeljebb 39 karakter lehet).
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


Gets value indicating that a header placeholder is present. Read boolean.

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
| isVisible | boolean | true – láthatóvá teszi a fejléc helyőrzőt, egyébként elrejti. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Sets text to slide header placeholder.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |