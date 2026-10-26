---
title: FontFallBackRule
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente la règle de secours de police
type: docs
url: /fr/com.aspose.slides/fontfallbackrule/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
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
| [get_Item(int index)](#get-Item-int-) | Obtient le nom de la police à l'indice spécifié. |
| [clear()](#clear--) | Supprime toutes les polices de la liste. |
| [remove(String fontName)](#remove-java.lang.String-) | Supprime la première occurrence d'une police FallBack spécifique de la liste. |
| [removeAt(int index)](#removeAt-int-) | Supprime la police FallBack à l'indice spécifié de la liste. |
| [toArray()](#toArray--) | Crée et renvoie un tableau contenant toutes les polices FallBack pour cette règle. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crée et renvoie un tableau contenant toutes les polices FallBack de la plage spécifiée dans la liste. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Renvoie l'indice de la règle spécifiée dans la collection. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Crée une nouvelle instance.

--------------------

> ```
> // Crée une nouvelle instance de FantFallBackRule avec une police.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Crée une nouvelle instance de FantFallBackRule avec plusieurs polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | long | Indice de départ de la plage Unicode |
| endIndex | long | Indice de fin de la plage Unicode |
| fontNames | java.lang.String | Nom ou noms de la police (séparés par des virgules) pour le FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


Crée une nouvelle instance.

--------------------

> ```
> // Crée une nouvelle instance de FantFallBackRule avec deux polices
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Crée une nouvelle instance de FantFallBackRule avec plusieurs polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | long | Indice de départ de la plage Unicode |
| endIndex | long | Indice de fin de la plage Unicode |
| fontNames | java.lang.String[] | Nom ou noms de la police (séparés par des virgules) pour le FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Ajoute une nouvelle police(s) à la liste des polices FallBack.

--------------------

> ```
> // Crée une nouvelle instance de FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Ajoute une deuxième police à la règle 
>  newRule.addFallBackFonts("MS Gothic");
>  //Ajoute une troisième et une quatrième police à la règle 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Nom ou noms de la police (séparés par des virgules) pour le FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Ajoute de nouvelles polices à la liste des polices FallBack.

--------------------

> ```
> // Crée une nouvelle instance de FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Ajoute trois autres polices à la règle 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | Nom ou noms de la police (séparés par des virgules) pour le FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Obtient le premier indice de la plage Unicode continue.

**Retour:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Obtient le premier indice de la plage Unicode continue.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Obtient le dernier indice de la plage Unicode continue.

**Retour:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Obtient le dernier indice de la plage Unicode continue.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Obtient le nombre de polices réellement définies pour la plage. Lecture seule int.

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Obtient le nom de la police à l'indice spécifié. Lecture seule [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour:**
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


Supprime la première occurrence d'une police FallBack spécifique de la liste.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Supprime Tahoma de la liste.
>  newRule.remove("Tahoma");
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Le nom de la police à supprimer de la liste. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Supprime la police FallBack à l'indice spécifié de la liste.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Supprime Tahoma de la liste.
>  newRule.remove(2);
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice zéro basé de la police à supprimer. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Crée et renvoie un tableau contenant toutes les polices FallBack pour cette règle.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Obtenez tous les noms de polices sous forme de tableau.
>  String[] fontNames = newRule.toArray();
> ```

**Retour:**
java.lang.String[] - Tableau de String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Crée et renvoie un tableau contenant toutes les polices FallBack de la plage spécifiée dans la liste.

```
 // Crée une règle contenant une liste de polices.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Obtenez les deux derniers noms de police sous forme de tableau.
 String[] fontNames = newRule.toArray(2, 2);
```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int | Un indice du premier police à ajouter. |
| count | int | Un nombre de polices à ajouter. |

**Retour:**
java.lang.String[] - Tableau de String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Renvoie l'indice de la règle spécifiée dans la collection.

--------------------

> ```
> // Crée une règle contenant une liste de polices.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Obtient l'indice de Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Nom de la police à rechercher. |

**Retour:**
int - Indice d'une police ou -1 si la police n'est pas trouvée dans la liste.