---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides for Android Java API hivatkozás
description: A menedzsert képviseli, amely a layout dia lábléc, dátum-idő, oldalszám helyőrzőinek viselkedését, valamint az összes gyermek helyőrzőt kezeli.
type: docs
url: /hu/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

A menedzser, amely a layout dia lábléc, dátum-idő és oldalszám helyőrzőinek viselkedését, valamint az összes gyermek helyőrzőt kezeli. A gyermek helyőrzők olyan helyőrzők, amelyek a függő diákon találhatók. A függő diák a layout diát használják és tőle függenek.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Módosítja a layout dia lábléchelyőrző és az összes gyermek lábléchelyőrző láthatóságát. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Módosítja a layout dia oldalszám helyőrző és az összes gyermek oldalszám helyőrző láthatóságát. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Módosítja a layout dia dátum-idő helyőrző és az összes gyermek dátum-idő helyőrző láthatóságát. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Beállítja a szöveget a layout dia lábléchelyőrzőre és az összes gyermek lábléchelyőrzőre. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Beállítja a szöveget a layout dia dátum-idő helyőrzőre és az összes gyermek dátum-idő helyőrzőre. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Módosítja a layout dia lábléchelyőrző és az összes gyermek lábléchelyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzők, amelyek a függő diákon vannak elhelyezve. A függő diák a master diát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - lábléchelyőrzőket láthatóvá tesz, egyébként - elrejti őket. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Módosítja a layout dia oldalszám helyőrző és az összes gyermek oldalszám helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzők, amelyek a függő diákon vannak elhelyezve. A függő diák a layout diát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - oldalszámhelyőrzőket láthatóvá tesz, egyébként - elrejti őket. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Módosítja a layout dia dátum-idő helyőrző és az összes gyermek dátum-idő helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzők, amelyek a függő diákon vannak elhelyezve. A függő diák a layout diát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - dátum-idő helyőrzőket láthatóvá tesz, egyébként - elrejti őket. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Beállítja a szöveget a layout dia lábléchelyőrzőre és az összes gyermek lábléchelyőrzőre. A gyermek helyőrzők olyan helyőrzők, amelyek a függő diákon vannak elhelyezve. A függő diák a layout diát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Beállítja a szöveget a layout dia dátum-idő helyőrzőre és az összes gyermek dátum-idő helyőrzőre. A gyermek helyőrzők olyan helyőrzők, amelyek a függő diákon vannak elhelyezve. A függő diák a layout diát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |