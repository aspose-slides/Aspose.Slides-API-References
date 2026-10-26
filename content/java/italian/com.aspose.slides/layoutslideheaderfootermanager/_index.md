---
title: LayoutSlideHeaderFooterManager
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta il gestore che contiene il comportamento dei segnaposti del piè di pagina, data/ora, numero di pagina della diapositiva di layout e di tutti i segnaposti figli.
type: docs
url: /it/com.aspose.slides/layoutslideheaderfootermanager/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Tutte le interfacce implementate:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Rappresenta il gestore che contiene il comportamento del segnaposto del piè di pagina della diapositiva di layout, del segnaposto data/ora, del segnaposto numero di pagina e di tutti i segnaposti figli. I segnaposti figli indicano segnaposti contenuti nelle diapositive dipendenti. Le diapositive dipendenti usano e dipendono dalla diapositiva di layout.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Modifica la visibilità del segnaposto del piè di pagina della diapositiva di layout e di tutti i segnaposti figli del piè di pagina. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Modifica la visibilità del segnaposto del numero di pagina della diapositiva di layout e di tutti i segnaposti figli del numero di pagina. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Modifica la visibilità del segnaposto data/ora della diapositiva di layout e di tutti i segnaposti figli data/ora. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Imposta il testo nel segnaposto del piè di pagina della diapositiva di layout e in tutti i segnaposti figli del piè di pagina. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Imposta il testo nel segnaposto data/ora della diapositiva di layout e in tutti i segnaposti figli data/ora. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto del piè di pagina della diapositiva di layout e di tutti i segnaposti figli del piè di pagina. I segnaposti figli indicano segnaposti contenuti nelle diapositive dipendenti. Le diapositive dipendenti usano e dipendono dalla diapositiva master.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibili i segnaposti del piè di pagina, altrimenti li nasconde. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto del numero di pagina della diapositiva di layout e di tutti i segnaposti figli del numero di pagina. I segnaposti figli indicano segnaposti contenuti nelle diapositive dipendenti. Le diapositive dipendenti usano e dipendono dalla diapositiva di layout.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibili i segnaposti del numero di pagina, altrimenti li nasconde. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto data/ora della diapositiva di layout e di tutti i segnaposti figli data/ora. I segnaposti figli indicano segnaposti contenuti nelle diapositive dipendenti. Le diapositive dipendenti usano e dipendono dalla diapositiva di layout.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibili i segnaposti data/ora, altrimenti li nasconde. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Imposta il testo nel segnaposto del piè di pagina della diapositiva di layout e in tutti i segnaposti figli del piè di pagina. I segnaposti figli indicano segnaposti contenuti nelle diapositive dipendenti. Le diapositive dipendenti usano e dipendono dalla diapositiva di layout.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Imposta il testo nel segnaposto data/ora della diapositiva di layout e in tutti i segnaposti figli data/ora. I segnaposti figli indicano segnaposti contenuti nelle diapositive dipendenti. Le diapositive dipendenti usano e dipendono dalla diapositiva di layout.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |