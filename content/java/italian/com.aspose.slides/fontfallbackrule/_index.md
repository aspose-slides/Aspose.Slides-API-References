---
title: FontFallBackRule
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta la regola di fallback del font
type: docs
url: /it/com.aspose.slides/fontfallbackrule/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Rappresenta la regola di fallback del font
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Crea una nuova istanza. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Crea una nuova istanza. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Aggiunge un nuovo font (o font) all'elenco dei font di fallback. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Aggiunge nuovi font all'elenco dei font di fallback. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Restituisce il primo indice dell'intervallo Unicode continuo. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Restituisce il primo indice dell'intervallo Unicode continuo. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Restituisce l'ultimo indice dell'intervallo Unicode continuo. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Restituisce l'ultimo indice dell'intervallo Unicode continuo. |
| [getCount()](#getCount--) | Restituisce il numero di font effettivamente definiti per l'intervallo. |
| [get_Item(int index)](#get-Item-int-) | Restituisce il nome del font all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti i font dall'elenco. |
| [remove(String fontName)](#remove-java.lang.String-) | Rimuove la prima occorrenza di un font di fallback specifico dall'elenco. |
| [removeAt(int index)](#removeAt-int-) | Rimuove il font di fallback all'indice specificato dell'elenco. |
| [toArray()](#toArray--) | Crea e restituisce un array con tutti i font di fallback per questa regola. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea e restituisce un array con tutti i font di fallback dell'intervallo specificato nell'elenco. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Restituisce l'indice della regola specificata nella collezione. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Crea una nuova istanza.

--------------------

> ```
> // Crea una nuova istanza di FantFallBackRule con un solo font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Crea una nuova istanza di FantFallBackRule con più font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | long | Indice iniziale dell'intervallo Unicode |
| endIndex | long | Indice finale dell'intervallo Unicode |
| fontNames | java.lang.String | Nome o nomi del font (separati da virgola) per il fallback |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


Crea una nuova istanza.

--------------------

> ```
> // Crea una nuova istanza di FantFallBackRule con due font
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Crea una nuova istanza di FantFallBackRule con più font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | long | Indice iniziale dell'intervallo Unicode |
| endIndex | long | Indice finale dell'intervallo Unicode |
| fontNames | java.lang.String[] | Nome o nomi del font (separati da virgola) per il fallback |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Aggiunge un nuovo font (o font) all'elenco dei font di fallback.

--------------------

> ```
> // Crea una nuova istanza di FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Aggiungi un secondo font alla regola 
>  newRule.addFallBackFonts("MS Gothic");
>  //Aggiungi un terzo e quarto font alla regola 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome o nomi del font (separati da virgola) per il fallback |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Aggiunge nuovi font all'elenco dei font di fallback.

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
| fontNames | java.lang.String[] | Nome o nomi del font (separati da virgola) per il fallback |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Restituisce il primo indice dell'intervallo Unicode continuo.

**Restituisce:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Restituisce il primo indice dell'intervallo Unicode continuo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Restituisce l'ultimo indice dell'intervallo Unicode continuo.

**Restituisce:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Restituisce l'ultimo indice dell'intervallo Unicode continuo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Restituisce il numero di font effettivamente definiti per l'intervallo. int di sola lettura.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Restituisce il nome del font all'indice specificato. Sola lettura [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

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


Rimuove tutti i font dall'elenco.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


Rimuove la prima occorrenza di un font di fallback specifico dall'elenco.

--------------------

> ```
> // Crea una regola che contiene un elenco di font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Rimuovi Tahoma dall'elenco.
>  newRule.remove("Tahoma");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome del font da rimuovere dall'elenco. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove il font di fallback all'indice specificato dell'elenco.

--------------------

> ```
> // Crea una regola che contiene un elenco di font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Rimuovendo Tahoma dall'elenco.
>  newRule.remove(2);
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice zero-based del font da rimuovere. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Crea e restituisce un array con tutti i font di fallback per questa regola.

--------------------

> ```
> // Crea una regola che contiene un elenco di font.
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


Crea e restituisce un array con tutti i font di fallback dell'intervallo specificato nell'elenco.

```
// Crea una regola che contiene un elenco di font.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Ottieni gli ultimi due nomi dei font in un array.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | Indice del primo font da aggiungere. |
| count | int | Numero di font da aggiungere. |

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
| fontName | java.lang.String | Nome del font da trovare. |

**Restituisce:**
int - Indice di un font o -1 se il font non è trovato nell'elenco.