---
title: IMathElementCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию математических элементов MathElement.
type: docs
url: /ru/com.aspose.slides/imathelementcollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Представляет коллекцию математических элементов (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [getCount()](#getCount--) | Получает количество элементов, реально содержащихся в коллекции. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Добавляет математический элемент в конец коллекции. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Определяет индекс конкретного математического элемента в коллекции. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Вставляет математический элемент в коллекцию по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Определяет, содержит ли коллекция конкретное значение. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Удаляет первое вхождение конкретного объекта из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу в коллекции. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Копирует в указанный массив. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента для получения |

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Получает количество элементов, реально содержащихся в коллекции. Только для чтения int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Возвращаемое значение:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```

Добавляет математический элемент в конец коллекции.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement, который следует добавить в конец коллекции. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

Определяет индекс конкретного математического элемента в коллекции.

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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Элемент, который необходимо найти в коллекции. |

**Возвращаемое значение:**
int - Индекс элемента, если он найден в коллекции; иначе -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

Вставляет математический элемент в коллекцию по указанному индексу.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому следует вставить IMathElement. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement для вставки. |

### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все элементы из коллекции.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```

Определяет, содержит ли коллекция конкретное значение.

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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Объект, который требуется найти в коллекции. |

**Возвращаемое значение:**
boolean - true, если объект найден в коллекции; иначе false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

Удаляет первое вхождение конкретного объекта из коллекции.

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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Объект, который следует удалить из коллекции. |

**Возвращаемое значение:**
boolean - true, если объект был успешно удалён; иначе false. Этот метод также возвращает false, если объект не найден в исходной коллекции.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет элемент по указанному индексу в коллекции.

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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который следует удалить. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

Копирует в указанный массив.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Массив для копирования. |
| arrayIndex | int | Индекс, с которого начинается копирование. |