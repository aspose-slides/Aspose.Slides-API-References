---
title: ITextSearchOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Představuje možnosti, které lze použít k vyhledávání textu v prezentaci, snímku nebo TextFrame.
type: docs
url: /cs/com.aspose.slides/itextsearchoptions/
---```
public interface ITextSearchOptions
```

Představuje možnosti, které lze použít k vyhledávání textu v Presentation, Slide nebo TextFrame.
## Metody

| Metoda | Popis |
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


Nastavte true pro rozlišování velikosti písmen, false - jinak. Čtení/zápis boolean.

**Vrací:**
boolean
### setCaseSensitive(boolean value) {#setCaseSensitive-boolean-}
```
public abstract void setCaseSensitive(boolean value)
```


Nastavte true pro rozlišování velikosti písmen, false - jinak. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getWholeWordsOnly() {#getWholeWordsOnly--}
```
public abstract boolean getWholeWordsOnly()
```


Nastavte true pro shodu pouze s celými slovy, false - jinak. Čtení/zápis boolean.

**Vrací:**
boolean
### setWholeWordsOnly(boolean value) {#setWholeWordsOnly-boolean-}
```
public abstract void setWholeWordsOnly(boolean value)
```


Nastavte true pro shodu pouze s celými slovy, false - jinak. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getIncludeNotes() {#getIncludeNotes--}
```
public abstract boolean getIncludeNotes()
```


Nastavte true pro zahrnutí textu obsaženého v poznámkách ke snímku při provádění vyhledávání textu, nahrazování nebo zvýraznění. Výchozí hodnota je false.

**Vrací:**
boolean
### setIncludeNotes(boolean value) {#setIncludeNotes-boolean-}
```
public abstract void setIncludeNotes(boolean value)
```


Nastavte true pro zahrnutí textu obsaženého v poznámkách ke snímku při provádění vyhledávání textu, nahrazování nebo zvýraznění. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |