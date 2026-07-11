---
title: IMathBlockCollection
second_title: Справочник по API Aspose.Slides для Android
description: Коллекция математических блоков IMathBlock
type: docs
url: /ru/com.aspose.slides/imathblockcollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Коллекция математических блоков (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Добавляет IMathBlock в конец коллекции. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Вставляет IMathBlock в коллекцию по указанному индексу. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Удаляет первое вхождение указанного объекта из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу коллекции. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Определяет, содержит ли коллекция указанное значение. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Определяет индекс указанного IMathBlock в коллекции. |
| [getCount()](#getCount--) | Получает количество элементов, фактически содержащихся в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Получает элемент по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
### add(IMMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Добавляет IMathBlock в конец коллекции.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Математический блок, который будет добавлен в конец коллекции |

### insert(int index, IMMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Вставляет IMMathBlock в коллекцию по указанному индексу.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому должен быть вставлен элемент. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | IMMathBlock, который необходимо вставить. |

### remove(IMMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Удаляет первое вхождение указанного объекта из коллекции.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Объект для удаления из коллекции. |

**Возвращаемое значение:**
boolean - true если элемент был успешно удалён из коллекции; в противном случае false. Этот метод также возвращает false, если элемент не найден в исходной коллекции.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет элемент по указанному индексу коллекции.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который следует удалить. |

### contains(IMMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

Определяет, содержит ли коллекция указанное значение.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Объект для поиска в коллекции. |

**Возвращаемое значение:**
boolean - true если элемент найден в коллекции; в противном случае false.

### indexOf(IMMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Определяет индекс указанного IMMathBlock в коллекции.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Элемент для поиска в коллекции. |

**Возвращаемое значение:**
int - Индекс элемента, если найден в коллекции; иначе -1.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Получает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Возвращаемое значение:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который следует получить. |

**Возвращаемое значение:**
[IMathBlock](../../com.aspose.slides/imathblock) - Блок математического текста.

### set_Item(int index, IMMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Получает элемент по указанному индексу. Только для чтения [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который следует установить. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Блок математического текста. |

### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все элементы из коллекции.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```