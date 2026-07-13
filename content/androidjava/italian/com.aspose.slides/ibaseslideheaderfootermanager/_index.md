---
title: IBaseSlideHeaderFooterManager
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta il manager che gestisce il comportamento dei segnaposti di piè di pagina, data-ora e numero di pagina per tutti i tipi di diapositiva.
type: docs
url: /it/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Rappresenta il manager che mantiene il comportamento dei segnaposti del piè di pagina, data-ora e numero di pagina per tutti i tipi di diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Ottiene il valore che indica la presenza di un segnaposto del piè di pagina. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Ottiene il valore che indica la presenza di un segnaposto del numero di pagina. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Ottiene il valore che indica la presenza di un segnaposto data-ora. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Modifica la visibilità del segnaposto del piè di pagina della diapositiva. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Modifica la visibilità del segnaposto del numero di pagina della diapositiva. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Modifica la visibilità del segnaposto data-ora della diapositiva. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Imposta il testo nel segnaposto del piè di pagina della diapositiva. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Imposta il testo nel segnaposto data-ora della diapositiva. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Ottiene il valore che indica la presenza di un segnaposto del piè di pagina. Legge boolean.

**Restituisce:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Ottiene il valore che indica la presenza di un segnaposto del numero di pagina. Legge boolean.

**Restituisce:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Ottiene il valore che indica la presenza di un segnaposto data-ora. Legge boolean.

**Restituisce:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto del piè di pagina della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibile un segnaposto del piè di pagina, altrimenti lo nasconde. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto del numero di pagina della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibile un segnaposto del numero di pagina, altrimenti lo nasconde. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto data-ora della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibile un segnaposto data-ora, altrimenti lo nasconde. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Imposta il testo nel segnaposto del piè di pagina della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Imposta il testo nel segnaposto data-ora della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |