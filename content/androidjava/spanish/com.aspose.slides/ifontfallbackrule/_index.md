---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: Representa la regla de respaldo de fuente
type: docs
url: /es/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Representa la regla de respaldo de fuente
## Métodos

| Method | Description |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Agrega una(s) nueva(s) fuente(s) a la lista de fuentes FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Agrega una(s) nueva(s) fuente(s) a la lista de fuentes FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Obtiene el primer índice del rango unicode continuo. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Obtiene el último índice del rango unicode continuo. |
| [getCount()](#getCount--) | Obtiene el número de fuentes realmente definidas para el rango. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el nombre de la fuente en el índice especificado. |
| [clear()](#clear--) | Elimina todas las fuentes de la lista. |
| [remove(String fontName)](#remove-java.lang.String-) | Elimina la primera aparición de una fuente FallBack específica de la lista. |
| [removeAt(int index)](#removeAt-int-) | Elimina la fuente FallBack en el índice especificado de la lista. |
| [toArray()](#toArray--) | Crea y devuelve una matriz con todas las fuentes FallBack para esta regla. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea y devuelve una matriz con todas las fuentes FallBack del rango especificado en la lista. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Devuelve un índice de la regla especificada en la colección. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Agrega una(s) nueva(s) fuente(s) a la lista de fuentes FallBack.

--------------------

> ```
> //Crear una nueva instancia de FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Agregar una segunda fuente a la regla 
>  newRule.addFallBackFonts("MS Gothic");
>  //Agregar una tercera y cuarta fuente a la regla 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Nombre(s) de la fuente (separados por comas) para FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Agrega una(s) nueva(s) fuente(s) a la lista de fuentes FallBack.

--------------------

> ```
> //Crear una nueva instancia de FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Agregar otras tres fuentes a la regla 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontNames | java.lang.String[] | Nombre(s) de la fuente (separados por comas) para FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Obtiene el primer índice del rango unicode continuo.

**Devuelve:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Obtiene el último índice del rango unicode continuo.

**Devuelve:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtiene el número de fuentes realmente definidas para el rango.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Obtiene el nombre de la fuente en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

Elimina todas las fuentes de la lista.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

Elimina la primera aparición de una fuente FallBack específica de la lista.

--------------------

> ```
> // Crear una regla que contiene una lista de fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Eliminando Tahoma de la lista
>  newRule.remove("Tahoma");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Nombre de la fuente a eliminar de la lista. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina la fuente FallBack en el índice especificado de la lista.

--------------------

> ```
> // Crear una regla que contiene una lista de fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Eliminando Tahoma de la lista
>  newRule.remove(2);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero de la fuente a eliminar. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Crea y devuelve una matriz con todas las fuentes FallBack para esta regla.

--------------------

> ```
> // Crear una regla que contiene una lista de fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Obtener todos los nombres de fuentes como arreglo
>  String[] fontNames = newRule.toArray();
> ```

**Devuelve:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Crea y devuelve una matriz con todas las fuentes FallBack del rango especificado en la lista.

--------------------

> ```
> // Crear una regla que contiene una lista de fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Obtener los dos últimos nombres de fuentes como arreglo
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Un índice de la primera fuente a agregar. |
| count | int | Un número de fuentes a agregar. |

**Devuelve:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Devuelve un índice de la regla especificada en la colección.

--------------------

> ```
> // Crear una regla que contiene una lista de fuentes.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Obtener el índice de Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Nombre de la fuente a buscar. |

**Devuelve:**
int - Index of a font or -1 if font not found in list.