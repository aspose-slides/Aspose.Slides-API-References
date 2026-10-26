---
title: IColorOperationCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection d'opérations de transformation de couleur.
type: docs
url: /fr/com.aspose.slides/icoloroperationcollection/
---
**Toutes les interfaces implémentées :**  
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Représente une collection d'opérations de transformation de couleur.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie ou définit l'opération à l'index spécifié. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Renvoie ou définit l'opération à l'index spécifié. |
| [add(int operation, float parameter)](#add-int-float-) | Ajoute une nouvelle opération à la fin de la collection. |
| [add(int operation)](#add-int-) | Ajoute une nouvelle opération à la fin de la collection. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Insère la nouvelle opération dans une collection. |
| [insert(int position, int operation)](#insert-int-int-) | Insère la nouvelle opération dans une collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'opération de couleur d'une collection. |
| [clear()](#clear--) | Supprime toutes les opérations de couleur. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

Renvoie ou définit l'opération à l'index spécifié. Lecture/écriture [IColorOperation](../../com.aspose.slides/icoloroperation).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retourne :**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

Renvoie ou définit l'opération à l'index spécifié. Lecture/écriture [IColorOperation](../../com.aspose.slides/icoloroperation).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

Ajoute une nouvelle opération à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| operation | int | Type d'opération. |
| parameter | float | Paramètre de l'opération. |

**Retourne :**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Opération ajoutée.

### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

Ajoute une nouvelle opération à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| operation | int | Type d'opération. |

**Retourne :**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Opération ajoutée.

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

Insère la nouvelle opération dans une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | int | L'index auquel l'opération sera insérée. |
| operation | int | Type d'opération. |
| parameter | float | Paramètre de l'opération. |

**Retourne :**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Opération insérée.

### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

Insère la nouvelle opération dans une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | int | L'index auquel l'opération sera insérée. |
| operation | int | Type d'opération. |

**Retourne :**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Opération insérée.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime l'opération de couleur d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'une opération de couleur à supprimer. |

### clear() {#clear--}
```
public abstract void clear()
```

Supprime toutes les opérations de couleur.