---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides Androidra Java API hivatkozás
description: A menedzsert reprezentálja, amely a mesterjegyzet-diák lábléc, dátum-idő, oldal-szám helyőrzőinek és az összes gyermek helyőrzőnek a viselkedését tartalmazza.
type: docs
url: /hu/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Ez a menedzsert reprezentálja, amely a mesterjegyzet-diák lábléc, dátum-idő és oldal-szám helyőrzőinek, valamint az összes gyermek helyőrzőnek a viselkedését tartalmazza. A gyermek helyőrzők olyan helyőrzőket jelentenek, amelyek a függő jegyzet-diákon vannak elhelyezve. A függő jegyzet-diák a mesterjegyzet-diára támaszkodnak és attól függenek.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Módosítja a mesterjegyzet-diának a fejlécre vonatkozó helyőrző és az összes gyermek fejléchez tartozó helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzőket jelentenek, amelyek a függő jegyzet-diákon vannak elhelyezve. A függő jegyzet-diák a mesterjegyzet-diára támaszkodnak és attól függenek. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Beállítja a szöveget a mesterjegyzet-diának a fejlécre vonatkozó helyőrzőbe és az összes gyermek fejlécre vonatkozó helyőrzőbe. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Módosítja a mesterjegyzet-diának a lábléc helyőrző és az összes gyermek lábléc helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzőket jelentenek, amelyek a függő jegyzet-diákon vannak elhelyezve. A függő jegyzet-diák a mesterjegyzet-diára támaszkodnak és attól függenek. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Módosítja a mesterjegyzet-diának az oldal-szám helyőrző és az összes gyermek oldal-szám helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzőket jelentenek, amelyek a függő jegyzet-diákon vannak elhelyezve. A függő jegyzet-diák a mesterjegyzet-diára támaszkodnak és attól függenek. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Módosítja a mesterjegyzet-diának a dátum-idő helyőrző és az összes gyermek dátum-idő helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzőket jelentenek, amelyek a függő jegyzet-diákon vannak elhelyezve. A függő jegyzet-diák a mesterjegyzet-diára támaszkodnak és attól függenek. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Beállítja a szöveget a mesterjegyzet-diának a lábléc helyőrzőbe és az összes gyermek lábléc helyőrzőbe. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Beállítja a szöveget a mesterjegyzet-diának a dátum-idő helyőrzőbe és az összes gyermek dátum-idő helyőrzőbe. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Módosítja a mesterjegyzet-diának a fejlécre vonatkozó helyőrző és az összes gyermek fejléchez tartozó helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzőket jelentenek, amelyek a függő jegyzet-diákon vannak elhelyezve. A függő jegyzet-diák a mesterjegyzet-diára támaszkodnak és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi a fejléc helyőrzőket, egyébként elrejti őket. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

Beállítja a szöveget a mesterjegyzet-diának a fejlécre vonatkozó helyőrzőbe és az összes gyermek fejlécre vonatkozó helyőrzőbe. A gyermek helyőrzők olyan helyőrzőket jelentenek, amelyek a függő jegyzet-diákon vannak elhelyezve. A függő jegyzet-diák a mesterjegyzet-diára támaszkodnak és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Módosítja a mesterjegyzet-diának a lábléc helyőrző és az összes gyermek lábléc helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzőket jelentenek, amelyek a függő jegyzet-diákon vannak elhelyezve. A függő jegyzet-diák a mesterjegyzet-diára támaszkodnak és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi a lábléc helyőrzőket, egyébként elrejti őket. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Módosítja a mesterjegyzet-diának az oldal-szám helyőrző és az összes gyermek oldal-szám helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzőket jelentenek, amelyek a függő jegyzet-diákon vannak elhelyezve. A függő jegyzet-diák a mesterjegyzet-diára támaszkodnak és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi az oldal-szám helyőrzőket, egyébként elrejti őket. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Módosítja a mesterjegyzet-diának a dátum-idő helyőrző és az összes gyermek dátum-idő helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzőket jelentenek, amelyek a függő jegyzet-diákon vannak elhelyezve. A függő jegyzet-diák a mesterjegyzet-diára támaszkodnak és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – láthatóvá teszi a dátum-idő helyőrzőket, egyébként elrejti őket. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Beállítja a szöveget a mesterjegyzet-diának a lábléc helyőrzőbe és az összes gyermek lábléc helyőrzőbe. A gyermek helyőrzők olyan helyőrzőket jelentenek, amelyek a függő jegyzet-diákon vannak elhelyezve. A függő jegyzet-diák a mesterjegyzet-diára támaszkodnak és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Beállítja a szöveget a mesterjegyzet-diának a dátum-idő helyőrzőbe és az összes gyermek dátum-idő helyőrzőbe. A gyermek helyőrzők olyan helyőrzőket jelentenek, amelyek a függő jegyzet-diákon vannak elhelyezve. A függő jegyzet-diák a mesterjegyzet-diára támaszkodnak és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |