---
title: IMasterSlideHeaderFooterManager
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta il gestore che contiene il comportamento dei segnaposti del piè di pagina, data-ora e numero di pagina della diapositiva master e di tutti i segnaposti dei figli.
type: docs
url: /it/com.aspose.slides/imasterslideheaderfootermanager/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Rappresenta il gestore che contiene il comportamento del segnaposto del piè di pagina, della data-ora e del numero di pagina della diapositiva master e di tutti i segnaposti dei figli. I segnaposti dei figli indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Modifica la visibilità del segnaposto del piè di pagina della diapositiva master e di tutti i segnaposti del piè di pagina dei figli. I segnaposti dei figli indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Modifica la visibilità del segnaposto del numero di pagina della diapositiva master e di tutti i segnaposti del numero di pagina dei figli. I segnaposti dei figli indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Modifica la visibilità del segnaposto della data e ora della diapositiva master e di tutti i segnaposti della data e ora dei figli. I segnaposti dei figli indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Imposta il testo nel segnaposto del piè di pagina della diapositiva master e in tutti i segnaposti del piè di pagina dei figli. I segnaposti dei figli indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Imposta il testo nel segnaposto della data e ora della diapositiva master e in tutti i segnaposti della data e ora dei figli. I segnaposti dei figli indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


Modifica la visibilità del segnaposto del piè di pagina della diapositiva master e di tutti i segnaposti del piè di pagina dei figli. I segnaposti dei figli indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposti del piè di pagina visibili, altrimenti li nasconde. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Modifica la visibilità del segnaposto del numero di pagina della diapositiva master e di tutti i segnaposti del numero di pagina dei figli. I segnaposti dei figli indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposti del numero di pagina visibili, altrimenti li nasconde. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Modifica la visibilità del segnaposto della data e ora della diapositiva master e di tutti i segnaposti della data e ora dei figli. I segnaposti dei figli indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende i segnaposti della data e ora visibili, altrimenti li nasconde. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


Imposta il testo nel segnaposto del piè di pagina della diapositiva master e in tutti i segnaposti del piè di pagina dei figli. I segnaposti dei figli indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


Imposta il testo nel segnaposto della data e ora della diapositiva master e in tutti i segnaposti della data e ora dei figli. I segnaposti dei figli indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |