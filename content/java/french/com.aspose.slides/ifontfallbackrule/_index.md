---
title: IFontFallBackRule
second_title: Aspose.Slides pour Java Référence API
description: Représente la règle de secours de police
type: docs
url: /fr/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Représente la règle de secours de police
## Méthodes

| Method | Description |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Ajoute une ou plusieurs nouvelles polices à la liste des polices de secours. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Ajoute de nouvelles polices à la liste des polices de secours. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Obtient le premier indice d'une plage Unicode continue. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Obtient le dernier indice d'une plage Unicode continue. |
| [getCount()](#getCount--) | Obtient le nombre de polices réellement définies pour la plage. |
| [get_Item(int index)](#get-Item-int-) | Obtient le nom de la police à l'indice spécifié. |
| [clear()](#clear--) | Supprime toutes les polices de la liste. |
| [remove(String fontName)](#remove-java.lang.String-) | Supprime la première occurrence d'une police de secours spécifique de la liste. |
| [removeAt(int index)](#removeAt-int-) | Supprime la police de secours à l'indice spécifié dans la liste. |
| [toArray()](#toArray--) | Crée et renvoie un tableau contenant toutes les polices de secours pour cette règle. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crée et renvoie un tableau contenant toutes les polices de secours de la plage spécifiée dans la liste. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Renvoie l'indice de la règle spécifiée dans la collection. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Ajoute une ou plusieurs nouvelles polices à la liste des polices de secours.

--------------------

> ```
> //Créer une nouvelle instance de FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Ajouter une deuxième police à la règle 
>  newRule.addFallBackFonts("MS Gothic");
>  //Ajouter une troisième et une quatrième police à la règle 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Nom ou noms de la police (délimités par des virgules) pour le secours |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Ajoute de nouvelles polices à la liste des polices de secours.

--------------------

> ```
> //Créer une nouvelle instance de FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Ajouter trois autres polices à la règle 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | Nom ou noms de la police (délimités par des virgules) pour le secours |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Obtient le premier indice d'une plage Unicode continue.

**Renvoie :**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Obtient le dernier indice d'une plage Unicode continue.

**Renvoie :**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtient le nombre de polices réellement définies pour la plage.

**Renvoie :**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Obtient le nom de la police à l'indice spécifié.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice zéro-base de la police dans la collection. |
| index | int |  |

**Renvoie :**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

Supprime toutes les polices de la liste.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

Supprime la première occurrence d'une police FallBack spécifique de la liste.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Suppression de Tahoma de la liste
>  newRule.remove("Tahoma");
```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Le nom de la police à supprimer de la liste. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime la police FallBack à l'index spécifié de la liste.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Suppression de Tahoma de la liste
>  newRule.remove(2);
```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de la police à supprimer. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Crée et renvoie un tableau contenant toutes les polices FallBack pour cette règle.

--------------------

> ```
> // Créer une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Obtenir tous les noms de police sous forme de tableau
>  String[] fontNames = newRule.toArray();
> ```

**Renvoie :**
java.lang.String[] - Tableau de String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Crée et renvoie un tableau contenant toutes les polices FallBack de la plage spécifiée dans la liste.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Obtenir les deux derniers noms de police sous forme de tableau
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int | L'indice de la première police à ajouter. |
| count | int | Un nombre de polices à ajouter. |

**Renvoie :**
java.lang.String[] - Tableau de String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Renvoie l'indice de la règle spécifiée dans la collection.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Obtenir l'index de Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Nom de la police à trouver. |

**Renvoie :**
int - Indice d'une police ou -1 si la police n'est pas trouvée dans la liste.