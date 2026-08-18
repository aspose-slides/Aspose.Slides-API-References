---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides Java API Referenciája
description: Egy menedzsert képvisel, amely a fő diára vonatkozó lábléc, dátum-idő, oldalszám helyőrzők és az összes gyermekhelyőrző viselkedését tartalmazza.
type: docs
url: /hu/com.aspose.slides/masterslideheaderfootermanager/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Minden megvalósított interfész:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

Egy menedzsert reprezentál, amely a fő diára vonatkozó lábléc, dátum-idő, oldalszám helyőrzők és az összes gyermekhelyőrző viselkedését tartalmazza. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő elrendezési diákon és a függő diákon vannak elhelyezve. A függő elrendezési diákok és diák a fő diát használják és tőle függenek.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Megváltoztatja a fő diára vonatkozó lábléc helyőrző és az összes gyermek lábléc helyőrző láthatóságát. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Megváltoztatja a fő diára vonatkozó oldalszám helyőrző és az összes gyermek oldalszám helyőrző láthatóságát. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Megváltoztatja a fő diára vonatkozó dátum-idő helyőrző és az összes gyermek dátum-idő helyőrző láthatóságát. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Beállítja a szöveget a fő diára vonatkozó lábléc helyőrzőben és az összes gyermek lábléc helyőrzőben. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Beállítja a szöveget a fő diára vonatkozó dátum-idő helyőrzőben és az összes gyermek dátum-idő helyőrzőben. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```


Megváltoztatja a fő diára vonatkozó lábléc helyőrző és az összes gyermek lábléc helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő elrendezési diákon és a függő diákon vannak elhelyezve. A függő elrendezési diákok és diák a fő diát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – lábléc helyőrzőket láthatóvá tesz, egyébként elrejti őket. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Megváltoztatja a fő diára vonatkozó oldalszám helyőrző és az összes gyermek oldalszám helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő elrendezési diákon és a függő diákon vannak elhelyezve. A függő elrendezési diákok és diák a fő diát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – oldalszám helyőrzőket láthatóvá tesz, egyébként elrejti őket. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Megváltoztatja a fő diára vonatkozó dátum-idő helyőrző és az összes gyermek dátum-idő helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő elrendezési diákon és a függő diákon vannak elhelyezve. A függő elrendezési diákok és diák a fő diát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – dátum-idő helyőrzőket láthatóvá tesz, egyébként elrejti őket. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```


Beállítja a szöveget a fő diára vonatkozó lábléc helyőrzőben és az összes gyermek lábléc helyőrzőben. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő elrendezési diákon és a függő diákon vannak elhelyezve. A függő elrendezési diákok és diák a fő diát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```


Beállítja a szöveget a fő diára vonatkozó dátum-idő helyőrzőben és az összes gyermek dátum-idő helyőrzőben. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő elrendezési diákon és a függő diákon vannak elhelyezve. A függő elrendezési diákok és diák a fő diát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |