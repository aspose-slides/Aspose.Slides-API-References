---
title: FontFallBackRule
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta la regola di fallback dei caratteri
type: docs
url: /it/com.aspose.slides/fontfallbackrule/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Rappresenta la regola di fallback dei caratteri
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Crea una nuova istanza. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Crea una nuova istanza. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Aggiunge un nuovo/i carattere/i all'elenco dei caratteri FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Aggiunge nuovi caratteri all'elenco dei caratteri FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Ottiene il primo indice di un intervallo Unicode continuo. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Ottiene il primo indice di un intervallo Unicode continuo. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Ottiene l'ultimo indice di un intervallo Unicode continuo. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Ottiene l'ultimo indice di un intervallo Unicode continuo. |
| [getCount()](#getCount--) | Ottiene il numero di caratteri effettivamente definiti per l'intervallo. |
| [get_Item(int index)](#get-Item-int-) | Ottiene il nome del carattere all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti i caratteri dall'elenco. |
| [remove(String fontName)](#remove-java.lang.String-) | Rimuove la prima occorrenza di un carattere specifico FallBack dall'elenco. |
| [removeAt(int index)](#removeAt-int-) | Rimuove il carattere FallBack all'indice specificato dell'elenco. |
| [toArray()](#toArray--) | Crea e restituisce un array con tutti i caratteri FallBack per questa regola. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea e restituisce un array con tutti i caratteri FallBack dall'intervallo specificato nell'elenco. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Restituisce l'indice della regola specificata nella collezione. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Crea una nuova istanza.

--------------------

> ```
> // Crea una nuova istanza di FantFallBackRule con un font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Crea una nuova istanza di FantFallBackRule con più font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | long | Indice iniziale dell'intervallo Unicode |
| endIndex | long | Indice finale dell'intervallo Unicode |
| fontNames | java.lang.String | Nome o nomi del carattere (separati da virgola) per il FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


Crea una nuova istanza.

--------------------

> ```
> // Create new instance of FantFallBackRule with two fonts
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Create new instance of FantFallBackRule with several fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | long | Indice iniziale dell'intervallo Unicode |
| endIndex | long | Indice finale dell'intervallo Unicode |
| fontNames | java.lang.String[] | Nome o nomi del carattere (separati da virgola) per il FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Aggiunge un nuovo/i carattere/i all'elenco dei caratteri FallBack.

--------------------

> ```
> // Crea una nuova istanza di FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Aggiungi un secondo font alla regola 
>  newRule.addFallBackFonts("MS Gothic");
>  //Aggiungi il terzo e il quarto font alla regola 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome o nomi del carattere (separati da virgola) per il FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Aggiunge nuovi caratteri all'elenco dei caratteri FallBack.

--------------------

> ```
> //Create new instance of FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Add of another three fonts to the rule 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontNames | java.lang.String[] | Nome o nomi del carattere (separati da virgola) per il FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Ottiene il primo indice di un intervallo Unicode continuo.

**Restituisce:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Ottiene il primo indice di un intervallo Unicode continuo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Ottiene l'ultimo indice di un intervallo Unicode continuo.

**Restituisce:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Ottiene l'ultimo indice di un intervallo Unicode continuo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Ottiene il numero di caratteri effettivamente definiti per l'intervallo. Solo lettura int.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Ottiene il nome del carattere all'indice specificato. Solo lettura [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


Rimuove tutti i caratteri dall'elenco.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


Rimuove la prima occorrenza di un carattere specifico FallBack dall'elenco.

--------------------

> ```
> // Crea una regola che contiene una lista di font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Rimuovi Tahoma dall'elenco.
>  newRule.remove("Tahoma");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome del carattere da rimuovere dall'elenco. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove il carattere FallBack all'indice specificato dell'elenco.

--------------------

> ```
> // Crea una regola che contiene una lista di font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Rimuovendo Tahoma dalla lista.
>  newRule.remove(2);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice zero-based del carattere da rimuovere. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Crea e restituisce un array con tutti i caratteri FallBack per questa regola.

--------------------

> ```
> // Crea una regola che contiene una lista di font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Ottieni tutti i nomi dei font come array.
>  String[] fontNames = newRule.toArray();
> ```


**Restituisce:**
java.lang.String[] - Array di String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Crea e restituisce un array con tutti i caratteri FallBack dall'intervallo specificato nell'elenco.

```
// Crea una regola che contiene un elenco di font.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Minijo, MS Gothic, Tahoma, Times New Roman");
 // Ottieni gli ultimi due nomi di font come array.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | Indice del primo carattere da aggiungere. |
| count | int | Numero di caratteri da aggiungere. |

**Restituisce:**
java.lang.String[] - Array di String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Restituisce l'indice della regola specificata nella collezione.

--------------------

> ```
> // Crea una regola che contiene un elenco di font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Ottieni l'indice di Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome del carattere da trovare. |

**Restituisce:**
int - Indice di un carattere o -1 se il carattere non è stato trovato nell'elenco.