---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta il manager che contiene il comportamento dei segnaposti del piè di pagina, data-ora, numero di pagina della diapositiva master e di tutti i segnaposti figlio.
type: docs
url: /it/com.aspose.slides/imasterslideheaderfootermanager/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Rappresenta il gestore che contiene il comportamento del segnaposto del piè di pagina della diapositiva master, della data-ora, del numero di pagina e di tutti i segnaposti figlio. I segnaposti figlio indicano i segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Cambia la visibilità del segnaposto del piè di pagina della diapositiva master e di tutti i segnaposti piè di pagina figlio. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Cambia la visibilità del segnaposto del numero di pagina della diapositiva master e di tutti i segnaposti numero di pagina figlio. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Cambia la visibilità del segnaposto data-ora della diapositiva master e di tutti i segnaposti data-ora figlio. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Imposta il testo del segnaposto del piè di pagina della diapositiva master e di tutti i segnaposti piè di pagina figlio. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Imposta il testo del segnaposto data-ora della diapositiva master e di tutti i segnaposti data-ora figlio. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Cambia la visibilità del segnaposto del piè di pagina della diapositiva master e di tutti i segnaposti piè di pagina figlio. I segnaposti figlio indicano i segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposti del piè di pagina visibili, altrimenti li nasconde. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Cambia la visibilità del segnaposto del numero di pagina della diapositiva master e di tutti i segnaposti numero di pagina figlio. I segnaposti figlio indicano i segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposti del numero di pagina visibili, altrimenti li nasconde. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Cambia la visibilità del segnaposto data-ora della diapositiva master e di tutti i segnaposti data-ora figlio. I segnaposti figlio indicano i segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposti data-ora visibili, altrimenti li nasconde. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Imposta il testo del segnaposto del piè di pagina della diapositiva master e di tutti i segnaposti piè di pagina figlio. I segnaposti figlio indicano i segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Imposta il testo del segnaposto data-ora della diapositiva master e di tutti i segnaposti data-ora figlio. I segnaposti figlio indicano i segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |