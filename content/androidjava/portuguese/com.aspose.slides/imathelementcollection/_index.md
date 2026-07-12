---
title: IMathElementCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de elementos matemáticos MathElement.
type: docs
url: /pt/com.aspose.slides/imathelementcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Representa uma coleção de elementos matemáticos (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [getCount()](#getCount--) | Obtém o número de elementos realmente contidos na coleção. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Adiciona um elemento matemático ao final da coleção. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Determina o índice de um elemento matemático específico na coleção. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Insere um elemento matemático na coleção no índice especificado. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Determina se a coleção contém um valor específico. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado da coleção. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copia para o array especificado. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do item a ser obtido |

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Retorna:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```

Adiciona um elemento matemático ao final da coleção.

--------------------

> ```
> Exemplo:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | O IMathElement a ser adicionado ao final da coleção. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

Determina o índice de um elemento matemático específico na coleção.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | O elemento a ser localizado na coleção. |

**Retorna:**
int - O índice do item se encontrado na coleção; caso contrário, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

Insere um elemento matemático na coleção no índice especificado.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual o IMathElement deve ser inserido. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | O IMathElement a ser inserido. |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todos os elementos da coleção.

--------------------

> ```
> Exemplo:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```

Determina se a coleção contém um valor específico.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | O objeto a ser localizado na coleção. |

**Retorna:**
boolean - true se o item for encontrado na coleção; caso contrário, false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

Remove a primeira ocorrência de um objeto específico da coleção.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | O objeto a ser removido da coleção. |

**Retorna:**
boolean - true se o item foi removido com sucesso da coleção; caso contrário, false. Este método também retorna false se o item não for encontrado na coleção original.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove o elemento no índice especificado da coleção.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

Copia para o array especificado.

--------------------

> ```
> Exemplo:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Array para o qual copiar. |
| arrayIndex | int | Índice para iniciar a cópia. |