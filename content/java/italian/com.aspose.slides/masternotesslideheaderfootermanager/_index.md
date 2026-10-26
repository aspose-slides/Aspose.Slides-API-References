---
title: MasterNotesSlideHeaderFooterManager
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta il manager che gestisce il comportamento dei segnaposti del piè di pagina, della data-ora e del numero di pagina della diapositiva master delle note e di tutti i segnaposti figlio.
type: docs
url: /it/com.aspose.slides/masternotesslideheaderfootermanager/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

Rappresenta il manager che gestisce il comportamento dei segnaposti del piè di pagina, della data-ora e del numero di pagina della diapositiva master delle note, nonché di tutti i segnaposti figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive di note dipendenti. Le diapositive di note dipendenti utilizzano e dipendono dalla diapositiva master delle note.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Changes master notes slide header placeholder and all child header placeholders visibility. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Sets text to master notes slide header placeholder and all child header placeholders. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Changes master slide footer placeholder and all child footer placeholders visibility. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Changes master slide page number placeholder and all child page number placeholders visibility. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Changes master slide date-time placeholder and all child date-time placeholders visibility. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sets text to master slide footer placeholder and all child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sets text to master slide date-time placeholder and all child date-time placeholders. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto dell'intestazione della diapositiva master delle note e di tutti i segnaposti di intestazione figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive di note dipendenti. Le diapositive di note dipendenti utilizzano e dipendono dalla diapositiva master delle note.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true – rende visibili i segnaposti dell'intestazione, altrimenti – li nasconde. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

Imposta il testo del segnaposto dell'intestazione della diapositiva master delle note e di tutti i segnaposti di intestazione figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive di note dipendenti. Le diapositive di note dipendenti utilizzano e dipendono dalla diapositiva master delle note.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto del piè di pagina della diapositiva master e di tutti i segnaposti di piè di pagina figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive di note dipendenti. Le diapositive di note dipendenti utilizzano e dipendono dalla diapositiva master delle note.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true – rende visibili i segnaposti del piè di pagina, altrimenti – li nasconde. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto del numero di pagina della diapositiva master e di tutti i segnaposti del numero di pagina figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive di note dipendenti. Le diapositive di note dipendenti utilizzano e dipendono dalla diapositiva master delle note.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true – rende visibili i segnaposti del numero di pagina, altrimenti – li nasconde. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Modifica la visibilità del segnaposto della data-ora della diapositiva master e di tutti i segnaposti della data-ora figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive di note dipendenti. Le diapositive di note dipendenti utilizzano e dipendono dalla diapositiva master delle note.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true – rende visibili i segnaposti della data-ora, altrimenti – li nasconde. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Imposta il testo del segnaposto del piè di pagina della diapositiva master e di tutti i segnaposti del piè di pagina figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive di note dipendenti. Le diapositive di note dipendenti utilizzano e dipendono dalla diapositiva master delle note.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Imposta il testo del segnaposto della data-ora della diapositiva master e di tutti i segnaposti della data-ora figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive di note dipendenti. Le diapositive di note dipendenti utilizzano e dipendono dalla diapositiva master delle note.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |