---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides for Java API referencia
description: A menedzsert reprezentálja, amely a mesterdiák lábjegyzet, dátum-idő, oldalszám helyőrzőinek és az összes gyermek helyőrzőnek a viselkedését tartalmazza.
type: docs
url: /hu/com.aspose.slides/imasterslideheaderfootermanager/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

A mesterdia lábjegyzet, dátum-idő, oldalszám helyőrzőket és az összes gyermek helyőrzőt kezelő menedzsert reprezentálja. A gyermek helyőrzők olyan helyőrzők, amelyek függő elrendezés diákon és függő diákon találhatók. A függő elrendezés diák és a diák a mesterdiát használják és függenek tőle.
## Módszerek

| Method | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Megváltoztatja a mesterdia lábjegyzet helyőrző és az összes gyermek lábjegyzet helyőrző láthatóságát. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Megváltoztatja a mesterdia oldalszám helyőrző és az összes gyermek oldalszám helyőrző láthatóságát. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Megváltoztatja a mesterdia dátum-idő helyőrző és az összes gyermek dátum-idő helyőrző láthatóságát. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Szöveget állít be a mesterdia lábjegyzet helyőrzőre és az összes gyermek lábjegyzet helyőrzőre. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Szöveget állít be a mesterdia dátum-idő helyőrzőre és az összes gyermek dátum-idő helyőrzőre. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Megváltoztatja a mesterdia lábjegyzet helyőrző és az összes gyermek lábjegyzet helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzők, amelyek függő elrendezés diákon és függő diákon találhatók. A függő elrendezés diák és a diák a mesterdiát használják és függenek tőle.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - lábjegyzet helyőrzőket láthatóvá teszi, egyébként elrejti őket. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Megváltoztatja a mesterdia oldalszám helyőrző és az összes gyermek oldalszám helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzők, amelyek függő elrendezés diákon és függő diákon találhatók. A függő elrendezés diák és a diák a mesterdiát használják és függenek tőle.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - oldalszám helyőrzőket láthatóvá teszi, egyébként elrejti őket. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Megváltoztatja a mesterdia dátum-idő helyőrző és az összes gyermek dátum-idő helyőrző láthatóságát. A gyermek helyőrzők olyan helyőrzők, amelyek függő elrendezés diákon és függő diákon találhatók. A függő elrendezés diák és a diák a mesterdiát használják és függenek tőle.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - dátum-idő helyőrzőket láthatóvá teszi, egyébként elrejti őket. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Szöveget állít be a mesterdia lábjegyzet helyőrzőre és az összes gyermek lábjegyzet helyőrzőre. A gyermek helyőrzők olyan helyőrzők, amelyek függő elrendezés diákon és függő diákon találhatók. A függő elrendezés diák és a diák a mesterdiát használják és függenek tőle.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Szöveget állít be a mesterdia dátum-idő helyőrzőre és az összes gyermek dátum-idő helyőrzőre. A gyermek helyőrzők olyan helyőrzők, amelyek függő elrendezés diákon és függő diákon találhatók. A függő elrendezés diák és a diák a mesterdiát használják és függenek tőle.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |