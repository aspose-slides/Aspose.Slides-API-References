---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides Java API referencia
description: A menedzsert reprezentálja, amely a mester jegyzetdia lábléc, dátum-idő és oldalszám helyőrzőinek, valamint az összes gyermekhelyőrzőnek a viselkedését tárolja.
type: docs
url: /hu/com.aspose.slides/masternotesslideheaderfootermanager/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**Minden megvalósított interfész:**
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

A manager azt a viselkedést képviseli, amely a mester jegyzetdia láblécét, dátum-időt, oldalszám helyőrzőket és az összes gyermekhelyőrzőt tartalmazza. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiákon találhatók. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Módosítja a mester jegyzetdia fejléc helyőrzőjének és az összes gyermekfejléc helyőrző láthatóságát. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Beállítja a szöveget a mester jegyzetdia fejléc helyőrzőjéhez és az összes gyermekfejléc helyőrzőhöz. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Módosítja a mester diák lábléc helyőrzőjének és az összes gyermeklábléc helyőrző láthatóságát. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Módosítja a mester dia oldalszám helyőrzőjének és az összes gyermekoldalszám helyőrző láthatóságát. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Módosítja a mester dia dátum-idő helyőrzőjének és az összes gyermekdátum-idő helyőrző láthatóságát. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Beállítja a szöveget a mester dia lábléc helyőrzőjéhez és az összes gyermeklábléc helyőrzőhöz. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Beállítja a szöveget a mester dia dátum-idő helyőrzőjéhez és az összes gyermekdátum-idő helyőrzőhöz. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```


Módosítja a mester jegyzetdia fejléc helyőrzőjének és az összes gyermekfejléc helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiákon találhatók. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi a fejléc helyőrzőket, egyébként elrejti őket. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```


Beállítja a szöveget a mester jegyzetdia fejléc helyőrzőjéhez és az összes gyermekfejléc helyőrzőhöz. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiákon találhatók. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```


Módosítja a mester dia lábléc helyőrzőjének és az összes gyermeklábléc helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiákon találhatók. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi a lábléc helyőrzőket, egyébként elrejti őket. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Módosítja a mester dia oldalszám helyőrzőjének és az összes gyermekoldalszám helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiákon találhatók. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi az oldalszám helyőrzőket, egyébként elrejti őket. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Módosítja a mester dia dátum-idő helyőrzőjének és az összes gyermekdátum-idő helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiákon találhatók. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi a dátum-idő helyőrzőket, egyébként elrejti őket. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```


Beállítja a szöveget a mester dia lábléc helyőrzőjéhez és az összes gyermeklábléc helyőrzőhöz. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiákon találhatók. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```


Beállítja a szöveget a mester dia dátum-idő helyőrzőjéhez és az összes gyermekdátum-idő helyőrzőhöz. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiákon találhatók. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |