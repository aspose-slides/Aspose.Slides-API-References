---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides Java API hivatkozás
description: A menedzser, amely a layout slide lábléc, dátum-idő, oldalszám helyőrzők és az összes gyermekhelyőrző viselkedését tartalmazza.
type: docs
url: /hu/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

A menedzsert képviseli, amely a layout slide lábléc, date-time, page number helyőrzők és az összes gyermekhelyőrző viselkedését tartalmazza. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő diákon vannak. A függő diák a layout slide-et használják és rá támaszkodnak.

## Módszerek

| Metódus | Leírás |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Megváltoztatja a layout slide lábléc helyőrző és az összes gyermeklábléc helyőrző láthatóságát. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Megváltoztatja a layout slide page number helyőrző és az összes gyermek page number helyőrző láthatóságát. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Megváltoztatja a layout slide date-time helyőrző és az összes gyermek date-time helyőrző láthatóságát. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Beállítja a szöveget a layout slide lábléc helyőrzőre és az összes gyermeklábléc helyőrzőre. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Beállítja a szöveget a layout slide date-time helyőrzőre és az összes gyermek date-time helyőrzőre. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Megváltoztatja a layout slide lábléc helyőrző és az összes gyermeklábléc helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő diákon vannak. A függő diák a master slide-et használják és rá támaszkodnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - lábléc helyőrzőket láthatóvá teszi, egyébként elrejti őket. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Megváltoztatja a layout slide page numberhelyőrző és az összes gyermek page number helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő diákon vannak. A függő diák a layout slide-et használják és rá támaszkodnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - page number helyőrzőket láthatóvá teszi, egyébként elrejti őket. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Megváltoztatja a layout slide date-time helyőrző és az összes gyermek date-time helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő diákon vannak. A függő diák a layout slide-et használják és rá támaszkodnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - date-time helyőrzőket láthatóvá teszi, egyébként elrejti őket. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Beállítja a szöveget a layout slide lábléc helyőrzőre és az összes gyermeklábléc helyőrzőre. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő diákon vannak. A függő diák a layout slide-et használják és rá támaszkodnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Beállítja a szöveget a layout slide date-time helyőrzőre és az összes gyermek date-time helyőrzőre. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő diákon vannak. A függő diák a layout slide-et használják és rá támaszkodnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |