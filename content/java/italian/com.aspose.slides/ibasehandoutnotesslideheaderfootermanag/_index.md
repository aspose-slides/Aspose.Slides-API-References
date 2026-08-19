---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta il gestore che conserva il comportamento dei segnaposti, incluso il segnaposto di intestazione per tutti i tipi di diapositive di dispense e note.
type: docs
url: /it/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Rappresenta il gestore che conserva il comportamento dei segnaposti, incluso il segnaposto di intestazione per tutti i tipi di diapositive di dispense e note.

--------------------

Il nome originale dell'interfaccia "IBaseHandoutNotesSlideHeaderFooterManager" è stato troncato a "IBaseHandoutNotesSlideHeaderFooterManag" per compatibilità COM (la lunghezza del nome del tipo non deve superare i 39).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Ottiene valore che indica la presenza di un segnaposto di intestazione. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Cambia la visibilità del segnaposto di intestazione della diapositiva. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Imposta il testo del segnaposto di intestazione della diapositiva. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Ottiene valore che indica la presenza di un segnaposto di intestazione. Leggi boolean.

**Restituisce:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


Cambia la visibilità del segnaposto di intestazione della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isVisible | boolean | true - rende visibile il segnaposto di intestazione, altrimenti lo nasconde. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Imposta il testo del segnaposto di intestazione della diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da impostare. |