---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: Represents font fallback rule
type: docs
url: /it/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Rappresenta la regola di fallback dei font
## Metodi

| Method | Description |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Aggiunge nuovi font(s) all'elenco dei font FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Aggiunge nuovi font all'elenco dei font FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Restituisce il primo indice dell'intervallo Unicode continuo. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Restituisce l'ultimo indice dell'intervallo Unicode continuo. |
| [getCount()](#getCount--) | Restituisce il numero di font effettivamente definiti per l'intervallo. |
| [get_Item(int index)](#get-Item-int-) | Restituisce il nome del font all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti i font dall'elenco. |
| [remove(String fontName)](#remove-java.lang.String-) | Rimuove la prima occorrenza di un font FallBack specifico dall'elenco. |
| [removeAt(int index)](#removeAt-int-) | Rimuove il font FallBack all'indice specificato dell'elenco. |
| [toArray()](#toArray--) | Crea e restituisce un array con tutti i font FallBack per questa regola. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea e restituisce un array con tutti i font FallBack dell'intervallo specificato nell'elenco. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Restituisce l'indice della regola specificata nella collezione. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Aggiunge un nuovo font(s) all'elenco dei font FallBack.

--------------------

> ```
> //Crea una nuova istanza di FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Aggiungi un secondo font alla regola 
>  newRule.addFallBackFonts("MS Gothic");
>  //Aggiungi un terzo e quarto font alla regola 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome o nomi del font (separati da virgola) per il FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Aggiunge nuovi font all'elenco dei font FallBack.

--------------------

> ```
> //Crea una nuova istanza di FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Aggiungi altri tre font alla regola 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontNames | java.lang.String[] | Nome o nomi del font (separati da virgola) per il FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Restituisce il primo indice dell'intervallo Unicode continuo.

**Restituisce:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Restituisce l'ultimo indice dell'intervallo Unicode continuo.

**Restituisce:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Restituisce il numero di font effettivamente definiti per l'intervallo.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Restituisce il nome del font all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti i font dall'elenco.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

Rimuove la prima occorrenza di un font FallBack specifico dall'elenco.

--------------------

> ```
> // Crea una regola che contiene un elenco di font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Rimozione di Tahoma dall'elenco
>  newRule.remove("Tahoma");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome del font da rimuovere dall'elenco. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove il font FallBack all'indice specificato dell'elenco.

--------------------

> ```
> // Crea una regola che contiene un elenco di font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Rimozione di Tahoma dall'elenco
>  newRule.remove(2);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice, a base zero, del font da rimuovere. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Crea e restituisce un array con tutti i font FallBack per questa regola.

--------------------

> ```
> // Crea una regola che contiene un elenco di font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Ottieni tutti i nomi dei font come array
>  String[] fontNames = newRule.toArray();
> ```


**Restituisce:**
java.lang.String[] - Array di String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Crea e restituisce un array con tutti i font FallBack dell'intervallo specificato nell'elenco.

--------------------

> ```
> // Crea una regola che contiene un elenco di font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Ottieni gli ultimi due nomi dei font come array
>  String[] fontNames = newRule.toArray(2,2);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | Indice del primo font da aggiungere. |
| count | int | Numero di font da aggiungere. |

**Restituisce:**
java.lang.String[] - Array di String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int index'indice(??)
```

Restituisce l'indice del font specificato nella collezione.

--------------------

> ```
> // Crea una regola che contiene un elenco di font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Ottieni l'indice di Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome del font da cercare. |

**Restituisce:**
int - Indice di un font o -1 se il font non è presente nell'elenco.