---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta il manager che gestisce il comportamento dei segnaposti del piè di pagina, della data-ora, del numero di pagina della diapositiva di layout e di tutti i segnaposti figli.
type: docs
url: /it/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Rappresenta il manager che contiene il comportamento del segnaposto del piè di pagina della diapositiva di layout, della data-ora, del numero di pagina e di tutti i segnaposti figli. I segnaposti figli indicano che i segnaposti sono contenuti nelle diapositive dipendenti. Le diapositive dipendenti utilizzano e dipendono dalla diapositiva di layout.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Modifica la visibilità del segnaposto del piè di pagina della diapositiva di layout e di tutti i segnaposti del piè di pagina figli. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Modifica la visibilità del segnaposto del numero di pagina della diapositiva di layout e di tutti i segnaposti del numero di pagina figli. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Modifica la visibilità del segnaposto della data-ora della diapositiva di layout e di tutti i segnaposti della data-ora figli. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Imposta il testo nel segnaposto del piè di pagina della diapositiva di layout e in tutti i segnaposti del piè di pagina figli. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Imposta il testo nel segnaposto della data-ora della diapositiva di layout e in tutti i segnaposti della data-ora figli. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto del piè di pagina della diapositiva di layout e di tutti i segnaposti del piè di pagina figli. I segnaposti figli indicano che i segnaposti sono contenuti nelle diapositive dipendenti. Le diapositive dipendenti utilizzano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibili i segnaposti del piè di pagina, altrimenti li nasconde. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto del numero di pagina della diapositiva di layout e di tutti i segnaposti del numero di pagina figli. I segnaposti figli indicano che i segnaposti sono contenuti nelle diapositive dipendenti. Le diapositive dipendenti utilizzano e dipendono dalla diapositiva di layout.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibili i segnaposti del numero di pagina, altrimenti li nasconde. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto della data-ora della diapositiva di layout e di tutti i segnaposti della data-ora figli. I segnaposti figli indicano che i segnaposti sono contenuti nelle diapositive dipendenti. Le diapositive dipendenti utilizzano e dipendono dalla diapositiva di layout.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibili i segnaposti della data-ora, altrimenti li nasconde. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Imposta il testo nel segnaposto del piè di pagina della diapositiva di layout e in tutti i segnaposti del piè di pagina figli. I segnaposti figli indicano che i segnaposti sono contenuti nelle diapositive dipendenti. Le diapositive dipendenti utilizzano e dipendono dalla diapositiva di layout.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Imposta il testo nel segnaposto della data-ora della diapositiva di layout e in tutti i segnaposti della data-ora figli. I segnaposti figli indicano che i segnaposti sono contenuti nelle diapositive dipendenti. Le diapositive dipendenti utilizzano e dipendono dalla diapositiva di layout.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |