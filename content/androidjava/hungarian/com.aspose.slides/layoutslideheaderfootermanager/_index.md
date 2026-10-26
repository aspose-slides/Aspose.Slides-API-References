---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides Android számára Java API-referencia
description: A menedzsert reprezentálja, amely az elrendezési dia lábléc, dátum-idő és oldalszám helyőrzőinek, valamint az összes gyermekhelyőrzőnek a viselkedését tartalmazza.
type: docs
url: /hu/com.aspose.slides/layoutslideheaderfootermanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

A menedzsert reprezentálja, amely az elrendezési dia lábléc, dátum-idő és oldalszám helyőrzőinek, valamint az összes gyermekhelyőrzőnek a viselkedését tartalmazza. A gyermekhelyőrzők olyan helyőrzőket jelentenek, amelyek a függő diákon találhatók. A függő diák az elrendezési diát használják és függnek tőle.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Changes layout slide footer placeholder and all child footer placeholders visibility. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Changes layout slide page number placeholder and all child page number placeholders visibility. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Changes layout slide date-time placeholder and all child date-time placeholders visibility. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sets text to layout slide footer placeholder and all child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sets text to layout slide date-time placeholder and all child date-time placeholders. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Módosítja az elrendezési dia lábléc helyőrzőjének és az összes gyermeklábléc helyőrzőnek a láthatóságát. A gyermekhelyőrzők olyan helyőrzőket jelentenek, amelyek a függő diákon találhatók. A függő diák a mester diát használják és függnek tőle.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - lábléc helyőrzőket láthatóvá tesz, egyébként - elrejti őket. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Módosítja az elrendezési dia oldalszám helyőrzőjének és az összes gyermekoldalszám helyőrzőnek a láthatóságát. A gyermekhelyőrzők olyan helyőrzőket jelentenek, amelyek a függő diákon találhatók. A függő diák az elrendezési diát használják és függnek tőle.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - oldalszám helyőrzőket láthatóvá tesz, egyébként - elrejti őket. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Módosítja az elrendezési dia dátum-idő helyőrzőjének és az összes gyermekdátum-idő helyőrzőnek a láthatóságát. A gyermekhelyőrzők olyan helyőrzőket jelentenek, amelyek a függő diákon találhatók. A függő diák az elrendezési diát használják és függnek tőle.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - dátum-idő helyőrzőket láthatóvá tesz, egyébként - elrejti őket. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Beállítja a szöveget az elrendezési dia lábléc helyőrzőjére és az összes gyermeklábléc helyőrzőre. A gyermekhelyőrzők olyan helyőrzőket jelentenek, amelyek a függő diákon találhatók. A függő diák az elrendezési diát használják és függnek tőle.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Beállítja a szöveget az elrendezési dia dátum-idő helyőrzőjére és az összes gyermekdátum-idő helyőrzőre. A gyermekhelyőrzők olyan helyőrzőket jelentenek, amelyek a függő diákon találhatók. A függő diák az elrendezési diát használják és függnek tőle.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |