---
title: ILayoutSlideHeaderFooterManager
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta il manager che gestisce il comportamento dei segnaposto del piè di pagina, della data-ora, del numero di pagina della diapositiva modello e tutti i segnaposto figlio.
type: docs
url: /it/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Rappresenta il manager che gestisce il comportamento dei segnaposto del piè di pagina, della data-ora e del numero di pagina della diapositiva modello e tutti i segnaposto figlio. I segnaposto figlio sono i segnaposto contenuti nelle diapositive dipendenti. Le diapositive dipendenti utilizzano e dipendono dalla diapositiva modello.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Modifica la visibilità del segnaposto del piè di pagina della diapositiva modello e di tutti i segnaposto figlio del piè di pagina. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Modifica la visibilità del segnaposto del numero di pagina della diapositiva modello e di tutti i segnaposto figlio del numero di pagina. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Modifica la visibilità del segnaposto della data-ora della diapositiva modello e di tutti i segnaposto figlio della data-ora. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Imposta il testo del segnaposto del piè di pagina della diapositiva modello e di tutti i segnaposto figlio del piè di pagina. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Imposta il testo del segnaposto della data-ora della diapositiva modello e di tutti i segnaposto figlio della data-ora. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto del piè di pagina della diapositiva modello e di tutti i segnaposto figlio del piè di pagina. I segnaposto figlio sono i segnaposto contenuti nelle diapositive dipendenti. Le diapositive dipendenti utilizzano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true – rende visibili i segnaposto del piè di pagina, altrimenti li nasconde. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto del numero di pagina della diapositiva modello e di tutti i segnaposto figlio del numero di pagina. I segnaposto figlio sono i segnaposto contenuti nelle diapositive dipendenti. Le diapositive dipendenti utilizzano e dipendono dalla diapositiva modello.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true – rende visibili i segnaposto del numero di pagina, altrimenti li nasconde. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto della data-ora della diapositiva modello e di tutti i segnaposto figlio della data-ora. I segnaposto figlio sono i segnaposto contenuti nelle diapositive dipendenti. Le diapositive dipendenti utilizzano e dipendono dalla diapositiva modello.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true – rende visibili i segnaposto della data-ora, altrimenti li nasconde. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Imposta il testo del segnaposto del piè di pagina della diapositiva modello e di tutti i segnaposto figlio del piè di pagina. I segnaposto figlio sono i segnaposto contenuti nelle diapositive dipendenti. Le diapositive dipendenti utilizzano e dipendono dalla diapositiva modello.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Imposta il testo del segnaposto della data-ora della diapositiva modello e di tutti i segnaposto figlio della data-ora. I segnaposto figlio sono i segnaposto contenuti nelle diapositive dipendenti. Le diapositive dipendenti utilizzano e dipendono dalla diapositiva modello.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |