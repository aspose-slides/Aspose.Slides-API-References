---
title: IMathBlockCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Coleção de blocos matemáticos IMathBlock
type: docs
url: /pt/com.aspose.slides/imathblockcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Coleção de blocos matemáticos (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Métodos

| Method | Description |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Adiciona IMathBlock ao final da coleção. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Insere IMathBlock na coleção no índice especificado. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove um item no índice especificado da coleção. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Determina se a coleção contém um valor específico. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Determina o índice de um IMathBlock específico na coleção. |
| [getCount()](#getCount--) | Obtém o número de elementos realmente contidos na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém o item no índice especificado. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Obtém o item no índice especificado. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Adiciona IMathBlock ao final da coleção.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Um bloco matemático que será adicionado ao final da coleção |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Insere IMathBlock na coleção no índice especificado.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```


**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual um item deve ser inserido. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | O IMathBlock a ser inserido. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Remove a primeira ocorrência de um objeto específico da coleção.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | O objeto a ser removido da coleção. |

**Retorna:**
boolean - true se o item foi removido com sucesso da coleção; caso contrário, false. Este método também retorna false se o item não for encontrado na coleção original.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove um item no índice especificado da coleção.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | O índice baseado em zero do item a ser removido. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

Determina se a coleção contém um valor específico.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | O objeto a ser localizado na coleção. |

**Retorna:**
boolean - true se o item for encontrado na coleção; caso contrário, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Determina o índice de um IMathBlock específico na coleção.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | O item a ser localizado na coleção. |

**Retorna:**
int - O índice do item se encontrado na coleção; caso contrário, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtém o número de elementos realmente contidos na coleção. int somente leitura.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

Obtém o item no índice especificado. somente leitura [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | O índice baseado em zero do item a ser obtido. |

**Retorna:**
[IMathBlock](../../com.aspose.slides/imathblock) - O bloco de um texto matemático.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Obtém o item no índice especificado. somente leitura [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | O índice baseado em zero do item a ser definido. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | O bloco de um texto matemático. |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todos os elementos da coleção.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```