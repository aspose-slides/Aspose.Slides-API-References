---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: Représente une règle de secours de police
type: docs
url: /fr/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Représente une règle de secours de police
## Méthodes

| Méthode | Description |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Ajoute une ou plusieurs nouvelles polices à la liste des polices de secours. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Ajoute une ou plusieurs nouvelles polices à la liste des polices de secours. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Obtient le premier indice de la plage Unicode continue. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Obtient le dernier indice de la plage Unicode continue. |
| [getCount()](#getCount--) | Obtient le nombre de polices réellement définies pour la plage. |
| [get_Item(int index)](#get-Item-int-) | Obtient le nom de la police à l'index spécifié. |
| [clear()](#clear--) | Supprime toutes les polices de la liste. |
| [remove(String fontName)](#remove-java.lang.String-) | Supprime la première occurrence d'une police FallBack spécifique de la liste. |
| [removeAt(int index)](#removeAt-int-) | Supprime la police FallBack à l'index spécifié de la liste. |
| [toArray()](#toArray--) | Crée et renvoie un tableau contenant toutes les polices FallBack pour cette règle. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crée et renvoie un tableau contenant toutes les polices FallBack de la plage spécifiée dans la liste. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Renvoie un indice de la règle spécifiée dans la collection. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```


Ajoute une ou plusieurs nouvelles polices à la liste des polices de secours.

--------------------

> ```
> //Create of new instance of FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Add a second font to the rule 
>  newRule.addFallBackFonts("MS Gothic");
>  //Add a third and fourth fonts to the rule 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Font's name or names (delimited by comma) for FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Adds a new fonts to the list of FallBack fonts.

--------------------

> ```
> //Création d'une nouvelle instance de FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Ajout de trois autres polices à la règle 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```
Get first index of continuous unicode range.

**Returns:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```
Get last index of continuous unicode range.

**Returns:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```
Gets the number of fonts actually defined for range.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```
Gets the font name at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```
Removes all fonts from the list.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

Removes the first occurrence of a specific FallBack font from the list.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Suppression de Tahoma de la liste
>  newRule.remove("Tahoma");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | The font's name to remove from the list. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Removes the FallBack font at the specified index of the list.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Suppression de Tahoma de la liste
>  newRule.remove(2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the font to remove. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```
Creates and returns an array with all FallBack fonts for this rule.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Récupère tous les noms de polices sous forme de tableau
>  String[] fontNames = newRule.toArray();
> ```

**Returns:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```


Crée et renvoie un tableau contenant toutes les polices FallBack de la plage spécifiée dans la liste.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Récupère les deux derniers noms de police sous forme de tableau
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first font to add. |
| count | int | A number of fonts to add. |

**Returns:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)


Renvoie un indice de la règle spécifiée dans la collection.

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Get index of Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Nom de la police à trouver. |

**Retour :**
int - Indice d'une police ou -1 si la police n'est pas trouvée dans la liste.