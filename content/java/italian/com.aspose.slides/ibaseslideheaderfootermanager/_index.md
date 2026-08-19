---
title: IBaseSlideHeaderFooterManager
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta il manager che gestisce il comportamento dei segnaposto di piè di pagina, data-ora e numero di pagina per tutti i tipi di diapositiva.
type: docs
url: /it/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Rappresenta il manager che contiene il comportamento dei segnaposto di piè di pagina, data-ora e numero di pagina per tutti i tipi di diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Restituisce il valore che indica la presenza di un segnaposto di piè di pagina. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Restituisce il valore che indica la presenza di un segnaposto di numero di pagina. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Restituisce il valore che indica la presenza di un segnaposto di data-ora. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Modifica la visibilità del segnaposto di piè di pagina della diapositiva. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Modifica la visibilità del segnaposto di numero di pagina della diapositiva. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Modifica la visibilità del segnaposto di data-ora della diapositiva. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Imposta il testo del segnaposto di piè di pagina della diapositiva. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Imposta il testo del segnaposto di data-ora della diapositiva. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```


Restituisce il valore che indica la presenza di un segnaposto di piè di pagina. Legge boolean.

**Restituisce:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```


Restituisce il valore che indica la presenza di un segnaposto di numero di pagina. Legge boolean.

**Restituisce:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```


Restituisce il valore che indica la presenza di un segnaposto di data-ora. Legge boolean.

**Restituisce:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```


Modifica la visibilità del segnaposto di piè di pagina della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibile un segnaposto di piè di pagina, altrimenti - lo nasconde. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```


Modifica la visibilità del segnaposto di numero di pagina della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibile un segnaposto di numero di pagina, altrimenti - lo nasconde. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```


Modifica la visibilità del segnaposto di data-ora della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibile un segnaposto di data-ora, altrimenti - lo nasconde. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```


Imposta il testo del segnaposto di piè di pagina della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```


Imposta il testo del segnaposto di data-ora della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |