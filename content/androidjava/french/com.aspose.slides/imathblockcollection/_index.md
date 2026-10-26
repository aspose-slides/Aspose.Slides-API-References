---
title: IMathBlockCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Collection de blocs mathématiques IMathBlock
type: docs
url: /fr/com.aspose.slides/imathblockcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Collection de blocs mathématiques (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Methods

| Method | Description |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Adds IMathBlock to the end of collection. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Inserts IMathBlock into the collection at the specified index. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Removes the first occurrence of a specific object from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes an item at the specified index of the collection. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Determines whether the collection contains a specific value. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Determines the index of a specific IMathBlock in collection. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the item at the specified index. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Gets the item at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Ajoute IMathBlock à la fin de la collection.

--------------------

> ```
> Exemple :
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Un bloc mathématique qui sera ajouté à la fin de la collection |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Insère IMathBlock dans la collection à l'index spécifié.

--------------------

> ```
> Exemple :
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel un élément doit être inséré. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'IMathBlock à insérer. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Supprime la première occurrence d'un objet spécifique de la collection.

--------------------

> ```
> Exemple :
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'objet à supprimer de la collection. |

**Retourne :**
boolean - true si l'élément a été supprimé avec succès de la collection ; sinon, false. Cette méthode renvoie également false si l'élément n'est pas trouvé dans la collection originale.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime un élément à l'index spécifié de la collection.

--------------------

> ```
> Exemple :
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

Détermine si la collection contient une valeur spécifique.

--------------------

> ```
> Exemple :
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'objet à rechercher dans la collection. |

**Retourne :**
boolean - true si l'élément est trouvé dans la collection ; sinon, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Détermine l'index d'un IMathBlock spécifique dans la collection.

--------------------

> ```
> Exemple :
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'élément à rechercher dans la collection. |

**Retourne :**
int - L'index de l'élément s'il est trouvé dans la collection ; sinon, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtient le nombre d'éléments réellement contenus dans la collection. int en lecture seule.

--------------------

> ```
> Exemple :
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
>  ```

**Retourne :**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Exemple :
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à obtenir. |

**Retourne :**
[IMathBlock](../../com.aspose.slides/imathblock) - Le bloc d'un texte mathématique.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Obtient l'élément à l'index spécifié. Lecture seule [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Exemple :
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à définir. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Le bloc d'un texte mathématique. |

### clear() {#clear--}
```
public abstract void clear()

Supprime tous les éléments de la collection.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```