---
title: FontFallBackRule
second_title: Aspose.Slides para Android a través de la API Java
description: Representa la regla de sustitución de fuentes
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

Representa la regla de sustitución de fuentes
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Crea una nueva instancia. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Crea una nueva instancia. |
## Métodos

| Método | Descripción |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Añade una(s) nueva(s) fuente(s) a la lista de fuentes de sustitución. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Añade nuevas fuentes a la lista de fuentes de sustitución. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Obtiene el primer índice del rango unicode continuo. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Obtiene el primer índice del rango unicode continuo. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Obtiene el último índice del rango unicode continuo. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Obtiene el último índice del rango unicode continuo. |
| [getCount()](#getCount--) | Obtiene el número de fuentes realmente definidas para el rango. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el nombre de la fuente en el índice especificado. |
| [clear()](#clear--) | Elimina todas las fuentes de la lista. |
| [remove(String fontName)](#remove-java.lang.String-) | Elimina la primera aparición de una fuente de sustitución específica de la lista. |
| [removeAt(int index)](#removeAt-int-) | Elimina la fuente de sustitución en el índice especificado de la lista. |
| [toArray()](#toArray--) | Crea y devuelve una matriz con todas las fuentes de sustitución para esta regla. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea y devuelve una matriz con todas las fuentes de sustitución del rango especificado en la lista. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Devuelve un índice de la regla especificada en la colección. |
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
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | long | Índice inicial del rango unicode |
| endIndex | long | Índice final del rango unicode |
| fontNames | java.lang.String | Nombre o nombres de la fuente (delimitados por coma) para sustitución |

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
| startIndex | long | Índice inicial del rango unicode |
| endIndex | long | Índice final del rango unicode |
| fontNames | java.lang.String[] | Nombre o nombres de la fuente (delimitados por coma) para sustitución |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Añade una(s) nueva(s) fuente(s) a la lista de fuentes de sustitución.

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
| fontName | java.lang.String | Nombre o nombres de la fuente (delimitados por coma) para sustitución |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Añade nuevas fuentes a la lista de fuentes de sustitución.

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
| fontNames | java.lang.String[] | Nombre o nombres de la fuente (delimitados por coma) para sustitución |

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


Establece el primer índice del rango unicode continuo.

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


Establece el último índice del rango unicode continuo.

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


Elimina la primera aparición de una fuente de sustitución específica de la lista.

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
| fontName | java.lang.String | Nombre de la fuente a eliminar de la lista. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina la fuente de sustitución en el índice especificado de la lista.

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
| index | int | Índice basado en cero de la fuente a eliminar. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Crea y devuelve una matriz con todas las fuentes de sustitución para esta regla.

--------------------

> ```
> // Crea una regla que contiene una lista de fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Obtiene todos los nombres de fuentes como matriz.
>  String[] fontNames = newRule.toArray();
> ```


**Devuelve:**
java.lang.String[] - Matriz de String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Crea y devuelve una matriz con todas las fuentes de sustitución del rango especificado en la lista.

```
 // Crea una regla que contiene una lista de fuentes.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Obtiene los dos últimos nombres de fuentes como matriz.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Índice del primer fuente a agregar. |
| count | int | Número de fuentes a agregar. |

**Devuelve:**
java.lang.String[] - Matriz de String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Devuelve un índice del elemento especificado en la colección.

--------------------

> ```
> // Crea una regla que contiene una lista de fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Obtiene el índice de Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Nombre de la fuente a buscar. |

**Devuelve:**
int - Índice de una fuente o -1 si la fuente no se encuentra en la lista.