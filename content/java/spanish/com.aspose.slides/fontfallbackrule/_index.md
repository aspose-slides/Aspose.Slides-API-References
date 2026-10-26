---
title: FontFallBackRule
second_title: Referencia de API de Aspose.Slides para Java
description: Representa la regla de reserva de fuentes
type: docs
url: /es/com.aspose.slides/fontfallbackrule/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Representa la regla de reserva de fuentes
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Crea una nueva instancia. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Crea una nueva instancia. |
## Métodos

| Método | Descripción |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Adds a new font(s) to the list of FallBack fonts. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Añade nuevas fuentes a la lista de fuentes de reserva. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Get first index of continuous unicode range. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Get first index of continuous unicode range. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Get last index of continuous unicode range. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Get last index of continuous unicode range. |
| [getCount()](#getCount--) | Gets the number of fonts actually defined for range. |
| [get_Item(int index)](#get-Item-int-) | Gets the font name at the specified index. |
| [clear()](#clear--) | Removes all fonts from the list. |
| [remove(String fontName)](#remove-java.lang.String-) | Removes the first occurrence of a specific FallBack font from the list. |
| [removeAt(int index)](#removeAt-int-) | Removes the FallBack font at the specified index of the list. |
| [toArray()](#toArray--) | Creates and returns an array with all FallBack fonts for this rule. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all FallBack fonts from the specified range in list. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Returns an index of the specified rule in the collection. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Crea una nueva instancia.

--------------------

> ```
> // Crea una nueva instancia de FantFallBackRule con una fuente.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Crea una nueva instancia de FantFallBackRule con varias fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | long | Índice inicial del rango Unicode |
| endIndex | long | Índice final del rango Unicode |
| fontNames | java.lang.String | Nombre o nombres de la fuente (separados por comas) para FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


Crea una nueva instancia.

--------------------

> ```
> // Crea una nueva instancia de FantFallBackRule con dos fuentes
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Crea una nueva instancia de FantFallBackRule con varias fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | long | Índice inicial del rango Unicode |
| endIndex | long | Índice final del rango Unicode |
| fontNames | java.lang.String[] | Nombre o nombres de la fuente (separados por comas) para FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Adds a new font(s) to the list of FallBack fonts.

--------------------

> ```
> // Crea una nueva instancia de FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Añade una segunda fuente a la regla 
>  newRule.addFallBackFonts("MS Gothic");
>  //Añade una tercera y cuarta fuentes a la regla 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Nombre o nombres de la fuente (separados por comas) para FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Añade nuevas fuentes a la lista de fuentes de reserva.

--------------------

> ```
> //Crea una nueva instancia de FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Añade otras tres fuentes a la regla 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontNames | java.lang.String[] | Nombre o nombres de la fuente (separados por comas) para FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Obtiene el primer índice del rango unicode continuo.

**Devuelve:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Obtiene el primer índice del rango unicode continuo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Obtiene el último índice del rango unicode continuo.

**Devuelve:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Obtiene el último índice del rango unicode continuo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Obtiene el número de fuentes realmente definidas para el rango. Solo lectura int.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Obtiene el nombre de la fuente en el índice especificado. Solo lectura [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


Elimina todas las fuentes de la lista.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


Elimina la primera aparición de una fuente FallBack específica de la lista.

--------------------

> ```
> // Crea una regla que contiene una lista de fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Elimina Tahoma de la lista.
>  newRule.remove("Tahoma");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | El nombre de la fuente a eliminar de la lista. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina la fuente FallBack en el índice especificado de la lista.

--------------------

> ```
> // Crea una regla que contiene una lista de fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Eliminando Tahoma de la lista.
>  newRule.remove(2);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero de la fuente a eliminar. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Crea y devuelve una matriz con todas las fuentes FallBack para esta regla.

--------------------

> ```
> // Crea una regla que contiene una lista de fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Obtiene todos los nombres de fuentes como una matriz.
>  String[] fontNames = newRule.toArray();
> ```

**Devuelve:**
java.lang.String[] - Matriz de String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Crea y devuelve una matriz con todas las fuentes FallBack del rango especificado en la lista.

```
// Crea una regla que contiene una lista de fuentes.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Obtiene los dos últimos nombres de fuentes como una matriz.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Un índice de la primera fuente a añadir. |
| count | int | Número de fuentes a añadir. |

**Devuelve:**
java.lang.String[] - Matriz de String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Devuelve un índice de la regla especificada en la colección.

--------------------

> ```
> // Crea una regla que contiene una lista de fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Minijo, MS Gothic, Tahoma, Times New Roman");
>  // Obtiene el índice de Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Nombre de la fuente a buscar. |

**Devuelve:**
int - Índice de una fuente o -1 si la fuente no se encuentra en la lista.