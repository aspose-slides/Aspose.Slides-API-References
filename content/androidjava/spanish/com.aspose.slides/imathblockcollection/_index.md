---
title: IMathBlockCollection
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Colección de bloques matemáticos IMathBlock
type: docs
url: /es/com.aspose.slides/imathblockcollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Colección de bloques matemáticos (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Agrega IMathBlock al final de la colección. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Inserta IMathBlock en la colección en el índice especificado. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Elimina la primera ocurrencia de un objeto específico de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina un elemento en el índice especificado de la colección. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Determina si la colección contiene un valor específico. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Determina el índice de un IMathBlock específico en la colección. |
| [getCount()](#getCount--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Obtiene el elemento en el índice especificado. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```


Agrega IMathBlock al final de la colección.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Un bloque matemático que se agregará al final de la colección |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```


Inserta IMathBlock en la colección en el índice especificado.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el cual se debe insertar un elemento. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | El IMathBlock a insertar. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```


Elimina la primera ocurrencia de un objeto específico de la colección.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | El objeto a eliminar de la colección. |

**Devuelve:**
boolean - true si el elemento se eliminó correctamente de la colección; de lo contrario, false. Este método también devuelve false si el elemento no se encuentra en la colección original.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Elimina un elemento en el índice especificado de la colección.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```


Determina si la colección contiene un valor específico.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | El objeto a localizar en la colección. |

**Devuelve:**
boolean - true si el elemento se encuentra en la colección; de lo contrario, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```


Determina el índice de un IMathBlock específico en la colección.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | El elemento a localizar en la colección. |

**Devuelve:**
int - El índice del elemento si se encuentra en la colección; de lo contrario, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```


Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```


Obtiene el elemento en el índice especificado. Solo lectura [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a obtener. |

**Devuelve:**
[IMathBlock](../../com.aspose.slides/imathblock) - El bloque de texto matemático.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```


Obtiene el elemento en el índice especificado. Solo lectura [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a establecer. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | El bloque de texto matemático. |

### clear() {#clear--}
```
public abstract void clear()
```


Elimina todos los elementos de la colección.

--------------------

> ```
> Ejemplo:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```