---
title: PresentationHeaderFooterManager
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta il gestore che contiene il comportamento di tutti i segnaposto di piè di pagina, data/ora e numero di pagina della presentazione.
type: docs
url: /it/com.aspose.slides/presentationheaderfootermanager/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)

**Tutte le interfacce implementate:**
[com.aspose.slides.IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
```
public class PresentationHeaderFooterManager extends BaseHeaderFooterManager implements IPresentationHeaderFooterManager
```

Rappresenta il gestore che contiene il comportamento di tutti i segnaposto di piè di pagina, data/ora e numero di pagina della presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Changes all header placeholders visibility, including notes master, notes slides and handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Changes all footer placeholders visibility, including master slides, layout slides, slides, notes master, notes slides and handout master. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Changes all page number placeholders visibility, including master slides, layout slides, slides, notes master, notes slides and handout master. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Changes all date-time placeholders visibility, including master slides, layout slides, slides, notes master, notes slides and handout master. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Sets text to all header placeholders, including notes master, notes slides and handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Sets text to all footer placeholders, including master slides, layout slides, slides, notes master, notes slides and handout master. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Sets text to all date-time placeholders, including master slides, layout slides, slides, notes master, notes slides and handout master. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Changes the footer, date-time and page number placeholders visibility for all title slides and for first layout slide. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public final void setAllHeadersVisibility(boolean isVisible)
```

Modifica la visibilità di tutti i segnaposto dell'intestazione, inclusi il master delle note, le diapositive delle note e il master del documento stampabile.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposto dell'intestazione visibili, altrimenti li nasconde. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public final void setAllFootersVisibility(boolean isVisible)
```

Modifica la visibilità di tutti i segnaposto del piè di pagina, inclusi le diapositive master, le diapositive di layout, le diapositive, il master delle note, le diapositive delle note e il master del documento stampabile.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposto del piè di pagina visibili, altrimenti li nasconde. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public final void setAllSlideNumbersVisibility(boolean isVisible)
```

Modifica la visibilità di tutti i segnaposto del numero di pagina, inclusi le diapositive master, le diapositive di layout, le diapositive, il master delle note, le diapositive delle note e il master del documento stampabile.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposto del numero di pagina visibili, altrimenti li nasconde. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public final void setAllDateTimesVisibility(boolean isVisible)
```

Modifica la visibilità di tutti i segnaposto data/ora, inclusi le diapositive master, le diapositive di layout, le diapositive, il master delle note, le diapositive delle note e il master del documento stampabile.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposto data/ora visibili, altrimenti li nasconde. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public final void setAllHeadersText(String text)
```

Imposta il testo a tutti i segnaposto dell'intestazione, inclusi il master delle note, le diapositive delle note e il master del documento stampabile.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public final void setAllFootersText(String text)
```

Imposta il testo a tutti i segnaposto del piè di pagina, inclusi le diapositive master, le diapositive di layout, le diapositive, il master delle note, le diapositive delle note e il master del documento stampabile.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public final void setAllDateTimesText(String text)
```

Imposta il testo a tutti i segnaposto data/ora, inclusi le diapositive master, le diapositive di layout, le diapositive, il master delle note, le diapositive delle note e il master del documento stampabile.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public final void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Modifica la visibilità dei segnaposto del piè di pagina, data/ora e numero di pagina per tutte le diapositive titolo e per la prima diapositiva di layout. Diapositive titolo \\u2013 diapositive basate sulla prima diapositiva di layout (indipendentemente dal tipo di questo primo layout).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposto visibili, altrimenti li nasconde. |