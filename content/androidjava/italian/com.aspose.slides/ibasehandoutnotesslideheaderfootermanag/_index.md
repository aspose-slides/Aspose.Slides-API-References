---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta il manager che conserva il comportamento dei segnaposti, incluso il segnaposto dell'intestazione per tutti i tipi di diapositive di dispensa e note.
type: docs
url: /it/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Rappresenta il manager che conserva il comportamento dei segnaposti, incluso il segnaposto dell'intestazione per tutti i tipi di diapositive di dispensa e note.

--------------------

Il nome originale dell'interfaccia "IBaseHandoutNotesSlideHeaderFooterManager" è stato troncato in "IBaseHandoutNotesSlideHeaderFooterManag" per compatibilità COM (la lunghezza del nome del tipo non deve superare i 39).

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Recupera il valore che indica la presenza di un segnaposto dell'intestazione. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Cambia la visibilità del segnaposto dell'intestazione della diapositiva. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Imposta il testo del segnaposto dell'intestazione della diapositiva. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

Recupera il valore che indica la presenza di un segnaposto dell'intestazione. Leggi boolean.

**Restituisce:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

Cambia la visibilità del segnaposto dell'intestazione della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende il segnaposto dell'intestazione visibile, altrimenti lo nasconde. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

Imposta il testo del segnaposto dell'intestazione della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |