---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides Androidra Java API hivatkozás alapján
description: A menedzsert reprezentálja, amely a mesterdia lábléc, dátum-idő és oldalszám helyőrzőit, valamint az összes gyermekhelyőrzőt kezeli.
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

A menedzsert reprezentálja, amely a mesterdia lábléc, dátum-idő és oldalszám helyőrzőinek, valamint az összes gyermekhelyőrzőnek a viselkedését tartalmazza. A gyermekhelyőrzők azt jelentik, hogy a helyőrzők függő elrendezési diákon és függő diákon találhatók. A függő elrendezési diák és a diák a mesterdiát használják és attól függenek.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Megváltoztatja a mesterdia lábléchelyőrző és az összes gyermeklábléchelyőrző láthatóságát. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Megváltoztatja a mesterdia oldalszám helyőrző és az összes gyermekoldalszám helyőrző láthatóságát. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Megváltoztatja a mesterdia dátum-idő helyőrző és az összes gyermekdátum-idő helyőrző láthatóságát. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Beállítja a szöveget a mesterdia lábléchelyőrző és az összes gyermeklábléchelyőrző számára. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Beállítja a szöveget a mesterdia dátum-idő helyőrző és az összes gyermekdátum-idő helyőrző számára. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Megváltoztatja a mesterdia lábléchelyőrző és az összes gyermeklábléchelyőrző láthatóságát. A gyermekhelyőrzők azt jelentik, hogy a helyőrzők függő elrendezési diákon és függő diákon találhatók. A függő elrendezési diák és a diák a mesterdiát használják és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – lábléchelyőrzőket láthatóvá teszi, egyébként elrejti őket. |
### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Megváltoztatja a mesterdia oldalszám helyőrző és az összes gyermekoldalszám helyőrző láthatóságát. A gyermekhelyőrzők azt jelentik, hogy a helyőrzők függő elrendezési diákon és függő diákon találhatók. A függő elrendezési diák és a diák a mesterdiát használják és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – oldalszám helyőrzőket láthatóvá teszi, egyébként elrejti őket. |
### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Megváltoztatja a mesterdia dátum-idő helyőrző és az összes gyermekdátum-idő helyőrző láthatóságát. A gyermekhelyőrzők azt jelentik, hogy a helyőrzők függő elrendezési diákon és függő diákon találhatók. A függő elrendezési diák és a diák a mesterdiát használják és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – dátum-idő helyőrzőket láthatóvá teszi, egyébként elrejti őket. |
### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Beállítja a szöveget a mesterdia lábléchelyőrző és az összes gyermeklábléchelyőrző számára. A gyermekhelyőrzők azt jelentik, hogy a helyőrzők függő elrendezési diákon és függő diákon találhatók. A függő elrendezési diák és a diák a mesterdiát használják és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |
### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Beállítja a szöveget a mesterdia dátum-idő helyőrző és az összes gyermekdátum-idő helyőrző számára. A gyermekhelyőrzők azt jelentik, hogy a helyőrzők függő elrendezési diákon és függő diákon találhatók. A függő elrendezési diák és a diák a mesterdiát használják és attól függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |