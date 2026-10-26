---
title: FontFallBackRule
second_title: Référence API Java d'Aspose.Slides pour Android
description: Représente la règle de secours de police
type: docs
url: /fr/com.aspose.slides/fontfallbackrule/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Représente la règle de secours de police
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Crée une nouvelle instance. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Crée une nouvelle instance. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Ajoute une ou plusieurs nouvelles polices à la liste des polices FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Ajoute de nouvelles polices à la liste des polices FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Obtient le premier indice de la plage Unicode continue. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Obtient le premier indice de la plage Unicode continue. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Obtient le dernier indice de la plage Unicode continue. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Obtient le dernier indice de la plage Unicode continue. |
| [getCount()](#getCount--) | Obtient le nombre de polices réellement définies pour la plage. |
| [get_Item(int index)](#get-Item-int-) | Obtient le nom de la police à l’indice spécifié. |
| [clear()](#clear--) | Supprime toutes les polices de la liste. |
| [remove(String fontName)](#remove-java.lang.String-) | Supprime la première occurrence d’une police FallBack spécifique de la liste. |
| [removeAt(int index)](#removeAt-int-) | Supprime la police FallBack à l’indice spécifié de la liste. |
| [toArray()](#toArray--) | Crée et renvoie un tableau contenant toutes les polices FallBack pour cette règle. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crée et renvoie un tableau contenant toutes les polices FallBack de la plage spécifiée dans la liste. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Retourne un indice de la règle spécifiée dans la collection. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Crée une nouvelle instance.

--------------------

> ```
> // Create new instance of FantFallBackRule with one font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Create new instance of FantFallBackRule with several fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | long | Start index of unicode range |
| endIndex | long | End index of unicode range |
| fontNames | java.lang.String | Font's name or names (delimited by comma) for FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

Creates new instance.

--------------------

> ```
> // Crée une nouvelle instance de FantFallBackRule avec deux polices
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Crée une nouvelle instance de FantFallBackRule avec plusieurs polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | long | Start index of unicode range |
| endIndex | long | End index of unicode range |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

Adds a new font(s) to the list of FallBack fonts.

--------------------

> ```
> // Crée une nouvelle instance de FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Ajoute une deuxième police à la règle 
>  newRule.addFallBackFonts("MS Gothic");
>  //Ajoute une troisième et une quatrième police à la règle 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | long | Start index of unicode range |
| endIndex | long | End index of unicode range |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

Adds a new fonts to the list of FallBack fonts.

--------------------

> ```
> //Crée une nouvelle instance de FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Ajoute trois autres polices à la règle 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

Get first index of continuous unicode range.

**Returns:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

Get first index of continuous unicode range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

Get last index of continuous unicode range.

**Returns:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

Get last index of continuous unicode range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

Gets the number of fonts actually defined for range. Read-only int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

Gets the font name at the specified index. Read-only [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

Supprime toutes les polices de la liste.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

Removes the first occurrence of a specific FallBack font from the list.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Supprime Tahoma de la liste.
>  newRule.remove("Tahoma");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | The font's name to remove from the list. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the FallBack font at the specified index of the list.

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Removing Tahoma from the list.
>  newRule.remove(2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the font to remove. |

### toArray() {#toArray--}
```
public final String[] toArray()
```
Creates and returns an array with all FallBack fonts for this rule.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Récupère tous les noms de polices sous forme de tableau.
>  String[] fontNames = newRule.toArray();
> ```

**Returns:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

Creates and returns an array with all FallBack fonts from the specified range in list.

```
// Create a rule contains a list of fonts.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Get a last two font names as array.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first font to add. |
| count | int | A number of fonts to add. |

**Returns:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)


Retourne un indice de la règle spécifiée dans la collection.

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Get index of Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Nom de la police à rechercher. |

**Retourne :**
int - Indice d'une police ou -1 si la police n'est pas trouvée dans la liste.