---
title: PresentationHeaderFooterManager
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta il gestore che controlla il comportamento di tutti i segnaposti di piè di pagina, data e ora e numero di pagina della presentazione.
type: docs
url: /it/com.aspose.slides/presentationheaderfootermanager/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)

**Tutte le interfacce implementate:**
[com.aspose.slides.IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
```
public class PresentationHeaderFooterManager extends BaseHeaderFooterManager implements IPresentationHeaderFooterManager
```

Rappresenta il gestore che controlla il comportamento di tutti i segnaposti del piè di pagina, di data e ora e dei numeri di pagina della presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Modifica la visibilità di tutti i segnaposti dell'intestazione, inclusi notes master, notes slides e handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Modifica la visibilità di tutti i segnaposti del piè di pagina, inclusi master slides, layout slides, slides, notes master, notes slides e handout master. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Modifica la visibilità di tutti i segnaposti di numero di pagina, inclusi master slides, layout slides, slides, notes master, notes slides e handout master. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Modifica la visibilità di tutti i segnaposti di data e ora, inclusi master slides, layout slides, slides, notes master, notes slides e handout master. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Imposta il testo per tutti i segnaposti dell'intestazione, inclusi notes master, notes slides e handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Imposta il testo per tutti i segnaposti del piè di pagina, inclusi master slides, layout slides, slides, notes master, notes slides e handout master. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Imposta il testo per tutti i segnaposti di data e ora, inclusi master slides, layout slides, slides, notes master, notes slides e handout master. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Modifica la visibilità dei segnaposti del piè di pagina, di data e ora e di numero di pagina per tutte le diapositiva titolo e per la prima diapositiva layout. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public final void setAllHeadersVisibility(boolean isVisible)
```

Modifica la visibilità di tutti i segnaposti dell'intestazione, inclusi notes master, notes slides e handout master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposti dell'intestazione visibili, altrimenti - li nasconde. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public final void setAllFootersVisibility(boolean isVisible)
```

Modifica la visibilità di tutti i segnaposti del piè di pagina, inclusi master slides, layout slides, slides, notes master, notes slides e handout master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposti del piè di pagina visibili, altrimenti - li nasconde. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public final void setAllSlideNumbersVisibility(boolean isVisible)
```

Modifica la visibilità di tutti i segnaposti di numero di pagina, inclusi master slides, layout slides, slides, notes master, notes slides e handout master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposti di numero di pagina visibili, altrimenti - li nasconde. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public final void setAllDateTimesVisibility(boolean isVisible)
```

Modifica la visibilità di tutti i segnaposti di data e ora, inclusi master slides, layout slides, slides, notes master, notes slides e handout master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposti di data e ora visibili, altrimenti - li nasconde. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public final void setAllHeadersText(String text)
```

Imposta il testo per tutti i segnaposti dell'intestazione, inclusi notes master, notes slides e handout master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public final void setAllFootersText(String text)
```

Imposta il testo per tutti i segnaposti del piè di pagina, inclusi master slides, layout slides, slides, notes master, notes slides e handout master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public final void setAllDateTimesText(String text)
```

Imposta il testo per tutti i segnaposti di data e ora, inclusi master slides, layout slides, slides, notes master, notes slides e handout master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public final void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Modifica la visibilità dei segnaposti del piè di pagina, di data e ora e di numero di pagina per tutte le diapositiva titolo e per la prima diapositiva layout. Le diapositiva titolo \\u2013 diapositive basate sulla prima diapositiva layout (indipendentemente dal tipo di questa prima layout).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposti visibili, altrimenti - li nasconde. |