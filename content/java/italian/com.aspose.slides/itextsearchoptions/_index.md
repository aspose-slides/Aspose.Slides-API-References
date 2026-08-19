---
title: ITextSearchOptions
second_title: Aspose.Slides for Java API Reference
description: Rappresenta le opzioni che possono essere usate per cercare testo in una Presentazione, Slide o TextFrame.
type: docs
url: /it/com.aspose.slides/itextsearchoptions/
---```
public interface ITextSearchOptions
```

Rappresenta le opzioni che possono essere usate per cercare testo in una Presentazione, Slide o TextFrame.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCaseSensitive()](#getCaseSensitive--) | Set true to use case-sensitive search, false - otherwise. |
| [setCaseSensitive(boolean value)](#setCaseSensitive-boolean-) | Set true to use case-sensitive search, false - otherwise. |
| [getWholeWordsOnly()](#getWholeWordsOnly--) | Set true to match only whole words, false - otherwise. |
| [setWholeWordsOnly(boolean value)](#setWholeWordsOnly-boolean-) | Set true to match only whole words, false - otherwise. |
| [getIncludeNotes()](#getIncludeNotes--) | Set true to include text contained in slide notes when performing text search, replacement, or highlighting operations. |
| [setIncludeNotes(boolean value)](#setIncludeNotes-boolean-) | Set true to include text contained in slide notes when performing text search, replacement, or highlighting operations. |
### getCaseSensitive() {#getCaseSensitive--}
```
public abstract boolean getCaseSensitive()
```


Imposta true per utilizzare la ricerca con distinzione tra maiuscole e minuscole, false altrimenti. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setCaseSensitive(boolean value) {#setCaseSensitive-boolean-}
```
public abstract void setCaseSensitive(boolean value)
```


Imposta true per utilizzare la ricerca con distinzione tra maiuscole e minuscole, false altrimenti. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getWholeWordsOnly() {#getWholeWordsOnly--}
```
public abstract boolean getWholeWordsOnly()
```


Imposta true per corrispondere solo parole intere, false altrimenti. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setWholeWordsOnly(boolean value) {#setWholeWordsOnly-boolean-}
```
public abstract void setWholeWordsOnly(boolean value)
```


Imposta true per corrispondere solo parole intere, false altrimenti. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getIncludeNotes() {#getIncludeNotes--}
```
public abstract boolean getIncludeNotes()
```


Imposta true per includere il testo contenuto nelle note della slide durante le operazioni di ricerca, sostituzione o evidenziazione del testo. Il valore predefinito è false.

**Restituisce:**
boolean
### setIncludeNotes(boolean value) {#setIncludeNotes-boolean-}
```
public abstract void setIncludeNotes(boolean value)
```


Imposta true per includere il testo contenuto nelle note della slide durante le operazioni di ricerca, sostituzione o evidenziazione del testo. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |