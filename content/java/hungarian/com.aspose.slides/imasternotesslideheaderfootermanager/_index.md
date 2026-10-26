---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides Java API referencia
description: Egy menedzsert képvisel, amely a fő jegyzetdia lábléc, dátum-idő, oldalszám helyőrzőinek és az összes gyermekhelyőrző viselkedését kezeli.
type: docs
url: /hu/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Represents manager which holds behavior of the master notes slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending notes slides. Depending notes slides use and depend on master notes slide.
## Metódusok

| Method | Description |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Módosítja a fő jegyzetdia fejléchelyőrzőjének és az összes gyermekfejléchelyőrző láthatóságát. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Beállítja a szöveget a fő jegyzetdia fejléchelyőrzőjébe és az összes gyermekfejléchelyőrzőbe. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Módosítja a fő jegyzetdia lábléchelyőrzőjének és az összes gyermeklábléchelyőrző láthatóságát. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Módosítja a fő jegyzetdia oldalszámhelyőrzőjének és az összes gyermekoldalszámhelyőrző láthatóságát. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Módosítja a fő jegyzetdia dátum-időhelyőrzőjének és az összes gyermekdátum-időhelyőrző láthatóságát. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Beállítja a szöveget a fő jegyzetdia lábléchelyőrzőjébe és az összes gyermeklábléchelyőrzőbe. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Beállítja a szöveget a fő jegyzetdia dátum-időhelyőrzőjébe és az összes gyermekdátum-időhelyőrzőbe. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```


Módosítja a fő jegyzetdia fejléchelyőrzőjének és az összes gyermekfejléchelyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiaokon találhatók. A függő jegyzetdiák a fő jegyzetdiát használják és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a fejléchez tartozó helyőrzőket, egyébként elrejti őket. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```


Beállítja a szöveget a fő jegyzetdia fejléchelyőrzőjébe és az összes gyermekfejléchelyőrzőbe. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiaokon találhatók. A függő jegyzetdiák a fő jegyzetdiát használják és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


Módosítja a fő jegyzetdia lábléchelyőrzőjének és az összes gyermeklábléchelyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiaokon találhatók. A függő jegyzetdiák a fő jegyzetdiát használják és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a lábléchez tartozó helyőrzőket, egyébként elrejti őket. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Módosítja a fő jegyzetdia oldalszámhelyőrzőjének és az összes gyermekoldalszámhelyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiaokon találhatók. A függő jegyzetdiák a fő jegyzetdiát használják és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi az oldalszámhoz tartozó helyőrzőket, egyébként elrejti őket. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Módosítja a fő jegyzetdia dátum-időhelyőrzőjének és az összes gyermekdátum-időhelyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiaokon találhatók. A függő jegyzetdiák a fő jegyzetdiát használják és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a dátum-időhöz tartozó helyőrzőket, egyébként elrejti őket. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


Beállítja a szöveget a fő jegyzetdia lábléchelyőrzőjébe és az összes gyermeklábléchelyőrzőbe. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiaokon találhatók. A függő jegyzetdiák a fő jegyzetdiát használják és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


Beállítja a szöveget a fő jegyzetdia dátum-időhelyőrzőjébe és az összes gyermekdátum-időhelyőrzőbe. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdiaokon találhatók. A függő jegyzetdiák a fő jegyzetdiát használják és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |