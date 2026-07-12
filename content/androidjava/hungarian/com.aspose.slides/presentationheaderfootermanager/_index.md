---
title: PresentationHeaderFooterManager
second_title: Aspose.Slides Android számára Java API referenciája
description: A prezentáció összes lábléc, dátum-idő és oldalszám-helyőrzőjének viselkedését kezelő menedzser.
type: docs
url: /hu/com.aspose.slides/presentationheaderfootermanager/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)

**Az összes megvalósított interfész:**
[com.aspose.slides.IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
```
public class PresentationHeaderFooterManager extends BaseHeaderFooterManager implements IPresentationHeaderFooterManager
```

A menedzser, amely a prezentáció összes lábléc-, dátum-idő- és oldalszám-helyőrzőjének viselkedését tartalmazza.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Módosítja az összes fejléchelyőrző láthatóságát, beleértve a jegyzet-mester, a jegyzet-diák és a szórólap-mestert. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Módosítja az összes lábléchelyőrző láthatóságát, beleértve a mesterdiák, elrendezési diák, diák, jegyzet-mester, jegyzet-diák és a szórólap-mestert. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Módosítja az összes oldalszám-helyőrző láthatóságát, beleértve a mesterdiák, elrendezési diák, diák, jegyzet-mester, jegyzet-diák és a szórólap-mestert. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Módosítja az összes dátum-idő-helyőrző láthatóságát, beleértve a mesterdiák, elrendezési diák, diák, jegyzet-mester, jegyzet-diák és a szórólap-mestert. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Beállítja a szöveget az összes fejléchelyőrzőre, beleértve a jegyzet-mestert, a jegyzet-diákat és a szórólap-mestert. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Beállítja a szöveget az összes lábléchelyőrzőre, beleértve a mesterdiákat, elrendezési diákat, diákat, jegyzet-mestert, jegyzet-diákat és a szórólap-mestert. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Beállítja a szöveget az összes dátum-idő-helyőrzőre, beleértve a mesterdiákat, elrendezési diákat, diákat, jegyzet-mestert, jegyzet-diákat és a szórólap-mestert. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Módosítja a lábléc-, dátum-idő- és oldalszám-helyőrzők láthatóságát az összes címdia és az első elrendezési dia esetén. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public final void setAllHeadersVisibility(boolean isVisible)
```

Módosítja az összes fejléchelyőrző láthatóságát, beleértve a jegyzet-mester, a jegyzet-diák és a szórólap-mestert.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a fejléchelyőrzőket, egyébként elrejti őket. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public final void setAllFootersVisibility(boolean isVisible)
```

Módosítja az összes lábléchelyőrző láthatóságát, beleértve a mesterdiák, elrendezési diák, diák, jegyzet-mester, jegyzet-diák és a szórólap-mestert.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a lábléchelyőrzőket, egyébként elrejti őket. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public final void setAllSlideNumbersVisibility(boolean isVisible)
```

Módosítja az összes oldalszám-helyőrző láthatóságát, beleértve a mesterdiák, elrendezési diák, diák, jegyzet-mester, jegyzet-diák és a szórólap-mestert.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi az oldalszám-helyőrzőket, egyébként elrejti őket. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public final void setAllDateTimesVisibility(boolean isVisible)
```

Módosítja az összes dátum-idő-helyőrző láthatóságát, beleértve a mesterdiák, elrendezési diák, diák, jegyzet-mester, jegyzet-diák és a szórólap-mestert.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a dátum-idő-helyőrzőket, egyébként elrejti őket. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public final void setAllHeadersText(String text)
```

Beállítja a szöveget az összes fejléchelyőrzőre, beleértve a jegyzet-mestert, a jegyzet-diákat és a szórólap-mestert.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public final void setAllFootersText(String text)
```

Beállítja a szöveget az összes lábléchelyőrzőre, beleértve a mesterdiákat, elrendezési diákat, diákat, jegyzet-mestert, jegyzet-diákat és a szórólap-mestert.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public final void setAllDateTimesText(String text)
```

Beállítja a szöveget az összes dátum-idő-helyőrzőre, beleértve a mesterdiákat, elrendezési diákat, diákat, jegyzet-mestert, jegyzet-diákat és a szórólap-mestert.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public final void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Módosítja a lábléc-, dátum-idő- és oldalszám-helyőrzők láthatóságát az összes címdia és az első elrendezési dia esetén. A címdiák – a első elrendezési diára alapuló diák (függetlenül az első elrendezés típusától).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true - láthatóvá teszi a helyőrzőket, egyébként elrejti őket. |