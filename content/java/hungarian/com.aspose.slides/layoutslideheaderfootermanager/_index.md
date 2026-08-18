---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides Java API Referenciája
description: A menedzser, amely a layout dia lábléc, dátum-idő és oldalszám helyőrzőinek, valamint az összes gyermek helyőrzőnek a viselkedését kezeli.
type: docs
url: /hu/com.aspose.slides/layoutslideheaderfootermanager/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Minden megvalósított interfész:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

A layout dia lábléc, dátum-idő és oldalszám helyőrzőinek, valamint minden gyermek helyőrzőnek a viselkedését kezelő menedzser. A gyermek helyőrzők azok a helyőrzők, amelyek a függő diákon találhatók. A függő diák a layout diát használják, és arra támaszkodnak.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Megváltoztatja a layout dia lábléc helyőrzőjének és az összes gyermek lábléc helyőrzőnek a láthatóságát. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Megváltoztatja a layout dia oldalszám helyőrzőjének és az összes gyermek oldalszám helyőrzőnek a láthatóságát. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Megváltoztatja a layout dia dátum-idő helyőrzőjének és az összes gyermek dátum-idő helyőrzőnek a láthatóságát. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Beállítja a szöveget a layout dia lábléc helyőrzőjéhez és az összes gyermek lábléc helyőrzőhöz. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Beállítja a szöveget a layout dia dátum-idő helyőrzőjéhez és az összes gyermek dátum-idő helyőrzőhöz. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Megváltoztatja a layout dia lábléc helyőrzőjének és az összes gyermek lábléc helyőrzőnek a láthatóságát. A gyermek helyőrzők olyan helyőrzők, amelyek a függő diákon találhatók. A függő diák a master diát használják, és arra támaszkodnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a lábléc helyőrzőket, egyébként elrejti őket. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Megváltoztatja a layout dia oldalszám helyőrzőjének és az összes gyermek oldalszám helyőrzőnek a láthatóságát. A gyermek helyőrzők olyan helyőrzők, amelyek a függő diákon találhatók. A függő diák a layout diát használják, és arra támaszkodnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi az oldalszám helyőrzőket, egyébként elrejti őket. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Megváltoztatja a layout dia dátum-idő helyőrzőjének és az összes gyermek dátum-idő helyőrzőnek a láthatóságát. A gyermek helyőrzők olyan helyőrzők, amelyek a függő diákon találhatók. A függő diák a layout diát használják, és arra támaszkodnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a dátum-idő helyőrzőket, egyébként elrejti őket. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Beállítja a szöveget a layout dia lábléc helyőrzőjéhez és az összes gyermek lábléc helyőrzőhöz. A gyermek helyőrzők olyan helyőrzők, amelyek a függő diákon találhatók. A függő diák a layout diát használják, és arra támaszkodnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Beállítja a szöveget a layout dia dátum-idő helyőrzőjéhez és az összes gyermek dátum-idő helyőrzőhöz. A gyermek helyőrzők olyan helyőrzők, amelyek a függő diákon találhatók. A függő diák a layout diát használják, és arra támaszkodnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |