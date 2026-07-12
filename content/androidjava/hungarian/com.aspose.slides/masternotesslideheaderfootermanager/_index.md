---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Egy menedzsert ábrázol, amely a master notes slide lábléc, dátum-idő és oldalszám helyőjeleit, valamint az összes gyermekhelyőjelet tartalmazza.
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

A manager olyan viselkedést képvisel, amely a master notes slide lábléc-, dátum-idő-, oldalszámhelyőjelek és az összes gyermekhelyőjelek működését tartalmazza. A gyermekhelyőjelek olyan helyőjelek, amelyek a függő jegyzet diákon találhatók. A függő jegyzet diák a master notes slide-ot használják és tőle függenek.

## Módszerek

| Metódus | Leírás |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Módosítja a master notes slide fejléchelyőjel és az összes gyermek fejléchelyőjel láthatóságát. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Szöveget állít be a master notes slide fejléchelyőjelhez és az összes gyermek fejléchelyőjelhez. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Módosítja a master slide lábléchelyőjel és az összes gyermek lábléchelyőjel láthatóságát. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Módosítja a master slide oldalszámhelyőjel és az összes gyermek oldalszámhelyőjel láthatóságát. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Módosítja a master slide dátum-idő helyőjel és az összes gyermek dátum-idő helyőjel láthatóságát. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Szöveget állít be a master slide lábléchelyőjelhez és az összes gyermek lábléchelyőjelhez. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Szöveget állít be a master slide dátum-idő helyőjelhez és az összes gyermek dátum-idő helyőjelhez. |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Módosítja a master notes slide fejléchelyőjel és az összes gyermek fejléchelyőjel láthatóságát. A gyermekhelyőjelek olyan helyőjelek, amelyek a függő jegyzet diákon találhatók. A függő jegyzet diák a master notes slide-ot használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a fejléchelyőjeleket, egyébként - elrejti őket. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

Szöveget állít be a master notes slide fejléchelyőjelhez és az összes gyermek fejléchelyőjelhez. A gyermekhelyőjelek olyan helyőjelek, amelyek a függő jegyzet diákon találhatók. A függő jegyzet diák a master notes slide-ot használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Módosítja a master slide lábléchelyőjel és az összes gyermek lábléchelyőjel láthatóságát. A gyermekhelyőjelek olyan helyőjelek, amelyek a függő jegyzet diákon találhatók. A függő jegyzet diák a master notes slide-ot használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a lábléchelyőjeleket, egyébként - elrejti őket. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Módosítja a master slide oldalszámhelyőjel és az összes gyermek oldalszámhelyőjel láthatóságát. A gyermekhelyőjelek olyan helyőjelek, amelyek a függő jegyzet diákon találhatók. A függő jegyzet diák a master notes slide-ot használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi az oldalszámhelyőjeleket, egyébként - elrejti őket. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Módosítja a master slide dátum-idő helyőjel és az összes gyermek dátum-idő helyőjel láthatóságát. A gyermekhelyőjelek olyan helyőjelek, amelyek a függő jegyzet diákon találhatók. A függő jegyzet diák a master notes slide-ot használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a dátum-idő helyőjeleket, egyébként - elrejti őket. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Szöveget állít be a master slide lábléchelyőjelhez és az összes gyermek lábléchelyőjelhez. A gyermekhelyőjelek olyan helyőjelek, amelyek a függő jegyzet diákon találhatók. A függő jegyzet diák a master notes slide-ot használják és tőle függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Szöveget állít be a master slide dátum-idő helyőjelhez és az összes gyermek dátum-idő helyőjelhez. A gyermekhelyőjelek olyan helyőjelek, amelyek a függő jegyzet diákon találhatók. A függő jegyzet diák a master notes slide-ot használják és tőlük függenek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |