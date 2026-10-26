---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta il gestore che contiene il comportamento di tutti i segnaposto di piè di pagina, data/ora e numero di pagina della presentazione.
type: docs
url: /it/com.aspose.slides/ipresentationheaderfootermanager/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Rappresenta il gestore che contiene il comportamento di tutti i segnaposto di piè di pagina, data/ora e numero di pagina della presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Modifica la visibilità di tutti i segnaposto dell'intestazione, inclusi il master delle note, le diapositive delle note e il master dei fogli di supporto. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Modifica la visibilità di tutti i segnaposto del piè di pagina, inclusi le diapositive master, le diapositive layout e le diapositive. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Modifica la visibilità di tutti i segnaposto del numero di pagina, inclusi le diapositive master, le diapositive layout e le diapositive. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Modifica la visibilità di tutti i segnaposto di data/ora, inclusi le diapositive master, le diapositive layout e le diapositive. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Imposta il testo per tutti i segnaposto dell'intestazione, inclusi il master delle note, le diapositive delle note e il master dei fogli di supporto. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Imposta il testo per tutti i segnaposto del piè di pagina, inclusi le diapositive master, le diapositive layout e le diapositive. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Imposta il testo per tutti i segnaposto di data/ora, inclusi le diapositive master, le diapositive layout e le diapositive. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Modifica la visibilità dei segnaposto del piè di pagina, di data/ora e del numero di pagina per tutte le diapositive titolo e per la prima diapositiva layout. Le diapositive titolo – diapositive basate sulla prima diapositiva layout (indipendentemente dal tipo di questo primo layout). |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Modifica la visibilità di tutti i segnaposto dell'intestazione, inclusi il master delle note, le diapositive delle note e il master dei fogli di supporto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposto dell'intestazione visibili, altrimenti li nasconde. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Modifica la visibilità di tutti i segnaposto del piè di pagina, inclusi le diapositive master, le diapositive layout e le diapositive.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposto del piè di pagina visibili, altrimenti li nasconde. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Modifica la visibilità di tutti i segnaposto del numero di pagina, inclusi le diapositive master, le diapositive layout e le diapositive.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposto del numero di pagina visibili, altrimenti li nasconde. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Modifica la visibilità di tutti i segnaposto di data/ora, inclusi le diapositive master, le diapositive layout e le diapositive.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposto di data/ora visibili, altrimenti li nasconde. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Imposta il testo per tutti i segnaposto dell'intestazione, inclusi il master delle note, le diapositive delle note e il master dei fogli di supporto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Imposta il testo per tutti i segnaposto del piè di pagina, inclusi le diapositive master, le diapositive layout e le diapositive.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Imposta il testo per tutti i segnaposto di data/ora, inclusi le diapositive master, le diapositive layout e le diapositive.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Modifica la visibilità dei segnaposto del piè di pagina, di data/ora e del numero di pagina per tutte le diapositive titolo e per la prima diapositiva layout. Le diapositive titolo – diapositive basate sulla prima diapositiva layout (indipendentemente dal tipo di questo primo layout).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposto visibili, altrimenti li nasconde. |