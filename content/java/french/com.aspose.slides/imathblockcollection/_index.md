---
title: IMathBlockCollection
second_title: Référence API Aspose.Slides pour Java
description: Collection de blocs mathématiques IMathBlock
type: docs
url: /fr/com.aspose.slides/imathblockcollection/
---
**Toutes les interfaces implémentées:**
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
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Ajoute IMathBlock à la fin de la collection. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Insère IMathBlock dans la collection à l'indice spécifié. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime un élément à l'indice spécifié de la collection. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Détermine si la collection contient une valeur spécifique. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Détermine l'indice d'un IMathBlock spécifique dans la collection. |
| [getCount()](#getCount--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'indice spécifié. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Obtient l'élément à l'indice spécifié. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Ajoute IMathBlock à la fin de la collection.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Un bloc mathématique qui sera ajouté à la fin de la collection |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Insère IMathBlock dans la collection à l'indice spécifié.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro auquel un élément doit être inséré. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Le IMathBlock à insérer. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Supprime la première occurrence d'un objet spécifique de la collection.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'objet à supprimer de la collection. |

**Retour:**
boolean - true si l'élément a été supprimé avec succès de la collection ; sinon, false. Cette méthode renvoie également false si l'élément n'est pas trouvé dans la collection d'origine.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime un élément à l'indice spécifié de la collection.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro de l'élément à supprimer. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

Détermine si la collection contient une valeur spécifique.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'objet à localiser dans la collection. |

**Retour:**
boolean - true si l'élément est trouvé dans la collection ; sinon, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Détermine l'indice d'un IMathBlock spécifique dans la collection.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'élément à localiser dans la collection. |

**Retour:**
int - L'indice de l'élément s'il est trouvé dans la collection ; sinon, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtient le nombre d'éléments réellement contenus dans la collection. int en lecture seule.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

Obtient l'élément à l'indice spécifié. [IMathBlock](../../com.aspose.slides/imathblock) en lecture seule.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro de l'élément à obtenir. |

**Retour:**
[IMathBlock](../../com.aspose.slides/imathblock) - Le bloc d'un texte mathématique.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Obtient l'élément à l'indice spécifié. [IMathBlock](../../com.aspose.slides/imathblock) en lecture seule.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro de l'élément à définir. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Le bloc d'un texte mathématique. |

### clear() {#clear--}
```
public abstract void clear()
```

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