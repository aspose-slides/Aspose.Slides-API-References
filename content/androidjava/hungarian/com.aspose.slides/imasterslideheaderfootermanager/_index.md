---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Olyan kezelőt képvisel, amely a mesterdia lábléc, dátum-idő, oldalszám helyőrzőinek és az összes gyermek helyőrzőnek a viselkedését tartja.
type: docs
url: /hu/com.aspose.slides/imasterslideheaderfootermanager/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Representálja azt a kezelőt, amely a mesterdiapozitív lábléc, dátum-idő és oldalszám helyőrzőinek, valamint az összes gyermek helyőrzőnek a viselkedését tartja. A gyermek helyőrzők azt jelentik, hogy a helyőrzők a függő elrendezési diákon és a függő diákon találhatók. A függő elrendezési diákok és diákok a mesterdiapozitívot használják és tőlük függenek.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | A mesterdiapozitív lábléc helyőrzőjének és az összes gyermek lábléc helyőrzőnek a láthatóságát módosítja. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | A mesterdiapozitív oldalszám helyőrzőjének és az összes gyermek oldalszám helyőrzőnek a láthatóságát módosítja. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | A mesterdiapozitív dátum-idő helyőrzőjének és az összes gyermek dátum-idő helyőrzőnek a láthatóságát módosítja. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Szöveget állít be a mesterdiapozitív lábléc helyőrzőjébe és az összes gyermek lábléc helyőrzőbe. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Szöveget állít be a mesterdiapozitív dátum-idő helyőrzőjébe és az összes gyermek dátum-idő helyőrzőbe. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


A mesterdiapozitív lábléc helyőrzőjének és az összes gyermek lábléc helyőrzőnek a láthatóságát módosítja. A gyermek helyőrzők azt jelentik, hogy a helyőrzők a függő elrendezési diákon és a függő diákon találhatók. A függő elrendezési diákok és diákok a mesterdiapozitívot használják és tőlük függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – lábléc helyőrzőket láthatóvá tesz, egyébként elrejti őket. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


A mesterdiapozitív oldalszám helyőrzőjének és az összes gyermek oldalszám helyőrzőnek a láthatóságát módosítja. A gyermek helyőrzők azt jelentik, hogy a helyőrzők a függő elrendezési diákon és a függő diákon találhatók. A függő elrendezési diákok és diákok a mesterdiapozitívot használják és tőlük függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – oldalszám helyőrzőket láthatóvá tesz, egyébként elrejti őket. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


A mesterdiapozitív dátum-idő helyőrzőjének és az összes gyermek dátum-idő helyőrzőnek a láthatóságát módosítja. A gyermek helyőrzők azt jelentik, hogy a helyőrzők a függő elrendezési diákon és a függő diákon találhatók. A függő elrendezési diákok és diákok a mesterdiapozitívot használják és tőlük függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – dátum-idő helyőrzőket láthatóvá tesz, egyébként elrejti őket. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


Szöveget állít be a mesterdiapozitív lábléc helyőrzőjébe és az összes gyermek lábléc helyőrzőbe. A gyermek helyőrzők azt jelentik, hogy a helyőrzők a függő elrendezési diákon és a függő diákon találhatók. A függő elrendezési diákok és diákok a mesterdiapozitívot használják és tőlük függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


Szöveget állít be a mesterdiapozitív dátum-idő helyőrzőjébe és az összes gyermek dátum-idő helyőrzőbe. A gyermek helyőrzők azt jelentik, hogy a helyőrzők a függő elrendezési diákon és a függő diákon találhatók. A függő elrendezési diákok és diákok a mesterdiapozitívot használják és tőlük függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |