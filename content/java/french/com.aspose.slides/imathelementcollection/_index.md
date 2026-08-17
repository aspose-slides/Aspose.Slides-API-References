---
title: IMathElementCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une collection d'éléments mathématiques MathElement.
type: docs
url: /fr/com.aspose.slides/imathelementcollection/
---
**Toutes les interfaces implémentées :**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable  
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Représente une collection d'éléments mathématiques (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [getCount()](#getCount--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Ajoute un élément mathématique à la fin de la collection. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Détermine l'index d'un élément mathématique spécifique dans la collection. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Insère un élément mathématique dans la collection à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Détermine si la collection contient une valeur spécifique. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié de la collection. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copier dans le tableau spécifié. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à obtenir |

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int.

--------------------

> ```
> Exemple:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Renvoie :**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```

Ajoute un élément mathématique à la fin de la collection.

--------------------

> ```
> Exemple:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Le IMathElement à ajouter à la fin de la collection. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

Détermine l'index d'un élément mathématique spécifique dans la collection.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'élément à localiser dans la collection. |

**Renvoie :**
int - L'index de l'élément s'il est trouvé dans la collection ; sinon, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

Insère un élément mathématique dans la collection à l'index spécifié.

--------------------

> ```
> Exemple:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel IMathElement doit être inséré. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Le IMathElement à insérer. |

### clear() {#clear--}
```
public abstract void clear()
```

Supprime tous les éléments de la collection.

--------------------

> ```
> Exemple:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```

Détermine si la collection contient une valeur spécifique.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'objet à localiser dans la collection. |

**Renvoie :**
boolean - true si l'élément est trouvé dans la collection ; sinon, false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

Supprime la première occurrence d'un objet spécifique de la collection.

--------------------

> ```
> Exemple:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'objet à supprimer de la collection. |

**Renvoie :**
boolean - true si l'élément a été supprimé avec succès de la collection ; sinon, false. Cette méthode renvoie également false si l'élément n'est pas trouvé dans la collection d'origine.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime l'élément à l'index spécifié de la collection.

--------------------

> ```
> Exemple:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

Copier dans le tableau spécifié.

--------------------

> ```
> Exemple:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Tableau dans lequel copier. |
| arrayIndex | int | Index à partir duquel commencer la copie. |