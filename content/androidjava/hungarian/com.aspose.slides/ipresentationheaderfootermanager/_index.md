---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides for Android Java API-referencia
description: A menedzsert reprezentálja, amely a prezentáció összes lábléc-dátum-idő- és oldalszám-helyőrzőjének viselkedését kezeli.
type: docs
url: /hu/com.aspose.slides/ipresentationheaderfootermanager/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

A menedzsert reprezentálja, amely a prezentáció összes lábléc-, dátum-idő- és oldalszám-helyőrzőjének viselkedését kezeli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | A fejléchelyőrzők láthatóságát változtatja, beleértve a notes master-t, a notes slide-okat és a handout master-t. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | A lábléchelyőrzők láthatóságát változtatja, beleértve a master slide-okat, a layout slide-okat és a slide-okat. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Az oldalszám-helyőrzők láthatóságát változtatja, beleértve a master slide-okat, a layout slide-okat és a slide-okat. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | A dátum-idő-helyőrzők láthatóságát változtatja, beleértve a master slide-okat, a layout slide-okat és a slide-okat. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Szöveget állít be minden fejléchelyőrzőre, beleértve a notes master-t, a notes slide-okat és a handout master-t. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Szöveget állít be minden lábléchelyőrzőre, beleértve a master slide-okat, a layout slide-okat és a slide-okat. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Szöveget állít be minden dátum-idő-helyőrzőre, beleértve a master slide-okat, a layout slide-okat és a slide-okat. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | A lábléc-, dátum-idő- és oldalszám-helyőrzők láthatóságát változtatja minden címdián és az első layout dián. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

A fejléchelyőrzők láthatóságát változtatja, beleértve a notes master-t, a notes slide-okat és a handout master-t.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – a fejléchelyőrzőket láthatóvá teszi, egyébként elrejti őket. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

A lábléchelyőrzők láthatóságát változtatja, beleértve a master slide-okat, a layout slide-okat és a slide-okat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – a lábléchelyőrzőket láthatóvá teszi, egyébként elrejti őket. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Az oldalszám-helyőrzők láthatóságát változtatja, beleértve a master slide-okat, a layout slide-okat és a slide-okat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – az oldalszám-helyőrzőket láthatóvá teszi, egyébként elrejti őket. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

A dátum-idő-helyőrzők láthatóságát változtatja, beleértve a master slide-okat, a layout slide-okat és a slide-okat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – a dátum-idő-helyőrzőket láthatóvá teszi, egyébként elrejti őket. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Szöveget állít be minden fejléchelyőrzőre, beleértve a notes master-t, a notes slide-okat és a handout master-t.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Szöveget állít be minden lábléchelyőrzőre, beleértve a master slide-okat, a layout slide-okat és a slide-okat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Szöveget állít be minden dátum-idő-helyőrzőre, beleértve a master slide-okat, a layout slide-okat és a slide-okat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

A lábléc, a dátum-idő és az oldalszám-helyőrzők láthatóságát változtatja minden címdián és az első layout dián. A címdiák – a első layout diára épülő diák (függetlenül attól, hogy ez az első layout milyen típusú).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – a helyőrzőket láthatóvá teszi, egyébként elrejti őket. |