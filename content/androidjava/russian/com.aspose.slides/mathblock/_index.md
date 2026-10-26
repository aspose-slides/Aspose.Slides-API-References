---
title: MathBlock
second_title: Aspose.Slides для Android через Java API Reference
description: Указывает экземпляр математического текста, содержащегося в MathParagraph и начинающегося с новой строки.
type: docs
url: /ru/com.aspose.slides/mathblock/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Указывает экземпляр математического текста, содержащийся в MathParagraph и начинающийся с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представлены в виде math block.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathBlock()](#MathBlock--) | Инициализирует новый экземпляр класса MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Создает новый математический блок и помещает в него указанный элемент. |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Создает новый математический блок и помещает в него указанные элементы. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Получает количество дочерних математических элементов, фактически содержащихся в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает или задает IMathElement по указанному индексу. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Получает или задает IMathElement по указанному индексу. |
| [isReadOnly()](#isReadOnly--) | Возвращает false, потому что коллекцию дочерних элементов можно изменять. |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
| [getParent_Immediate()](#getParent-Immediate--) | Возвращает объект Parent_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Добавляет математический элемент в конец коллекции. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Определяет, содержит ли коллекция указанное значение. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Копирует в указанный массив. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Удаляет первое вхождение указанного объекта из коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Определяет индекс конкретного математического элемента в коллекции. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Вставляет MathElement в коллекцию по указанному индексу. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу в коллекции. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Объединяет математический элемент с этим математическим блоком. |
| [join(String mathText)](#join-java.lang.String-) | Объединяет математический текст с этим математическим блоком. |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Объединяет другой математический блок с текущим. |
| [delimit(char separatorCharacter)](#delimit-char-) | Разделяет дочерние элементы символом-разделителем (без скобок). |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие символы, в качестве рамки. |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие, в качестве рамки и разделяет их символом-разделителем. |
| [toMathArray()](#toMathArray--) | Размещает дочерние элементы в вертикальном массиве. |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Сохраняет содержимое этого [MathBlock](../../com.aspose.slides/mathblock) как MathML. |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Инициализирует новый экземпляр класса MathBlock.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```

Создает новый математический блок и помещает в него указанный элемент.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Математический элемент, который будет помещён в блок. |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Создает новый математический блок и помещает в него указанные элементы.

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Математические элементы, которые будут помещены в блок. |

### getCount() {#getCount--}
```
public final int getCount()
```

Получает количество дочерних математических элементов, фактически содержащихся в коллекции. Только для чтения int.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Возвращает:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Получает или задает IMathElement по указанному индексу.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента. |

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement) - Математический элемент.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Получает или задает IMathElement по указанному индексу.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента. |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Математический элемент. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Возвращает false, потому что коллекцию дочерних элементов можно изменять.

**Возвращает:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Получить дочерние элементы

**Возвращает:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Добавляет математический элемент в конец коллекции.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement, который будет добавлен в конец коллекции. |

### clear() {#clear--}
```
public final void clear()
```

Удаляет все элементы из коллекции.

--------------------

> ```
> Пример:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

Определяет, содержит ли коллекция указанное значение.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Объект, который необходимо найти в коллекции. |

**Возвращает:**
boolean - true, если элемент найден в коллекции; иначе false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Копирует в указанный массив.

--------------------

> ```
> Пример:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Массив, в который производится копирование. |
| arrayIndex | int | Индекс, с которого начинается копирование. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Удаляет первое вхождение указанного объекта из коллекции.

--------------------

> ```
> Пример:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Объект, который необходимо удалить из коллекции. |

**Возвращает:**
boolean - true, если объект успешно удалён из коллекции; иначе false. Этот метод также возвращает false, если объект не найден в исходной коллекции.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Возвращает перечислитель, который перебирает коллекцию.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator - java.util.Iterator для всей коллекции.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Определяет индекс конкретного математического элемента в коллекции.

--------------------

> ```
> Пример:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Элемент, который необходимо найти в коллекции. |

**Возвращает:**
int - Индекс элемента, если он найден в коллекции; иначе -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Вставляет MathElement в коллекцию по указанному индексу.

--------------------

> ```
> Пример:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором должен быть вставлен MathElement. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | MathElement, который будет вставлен. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет элемент по указанному индексу в коллекции.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который необходимо удалить. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Объединяет математический элемент с этим математическим блоком.

--------------------

> ```
> Пример:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Элемент, который будет объединён. |

**Возвращает:**
[IMathBlock](../../com.aspose.slides/imathblock) - Текущий экземпляр IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Объединяет математический текст с этим математическим блоком.

--------------------

> ```
> Пример:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | java.lang.String | Математический текст, который будет объединён. |

**Возвращает:**
[IMathBlock](../../com.aspose.slides/imathblock) - Новый IMathBlock, содержащий текущий экземпляр и указанный аргумент
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Объединяет другой математический блок с текущим.

--------------------

> ```
> Пример:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Блок, который будет объединён. |

**Возвращает:**
[IMathBlock](../../com.aspose.slides/imathblock) - Этот математический блок после объединения
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Разделяет дочерние элементы символом-разделителем (без скобок).

--------------------

> ```
> Пример:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| separatorCharacter | char | Символ-разделитель. |

**Возвращает:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Математический элемент типа [IMathDelimiter](../../com.aspose.slides/imathdelimiter).
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие символы, в качестве рамки.

--------------------

> ```
> Пример:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| beginningCharacter | char | Начальный символ (обычно левая скобка). |
| endingCharacter | char | Конечный символ (обычно правая скобка). |

**Возвращает:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Математический элемент типа [IMathDelimiter](../../com.aspose.slides/imathdelimiter), который включает указанные символы в качестве рамки.
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие, в качестве рамки и разделяет их символом-разделителем.

--------------------

> ```
> Пример:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| beginningCharacter | char | Начальный символ (обычно левая скобка). |
| endingCharacter | char | Конечный символ (обычно правая скобка). |
| separatorCharacter | char | Символ-разделитель. |

**Возвращает:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Математический элемент типа [IMathDelimiter](../../com.aspose.slides/imathdelimiter), который включает указанные символы в качестве рамки и разделителя.
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Размещает дочерние элементы в вертикальном массиве.

--------------------

> ```
> Пример:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Возвращает:**
[IMathArray](../../com.aspose.slides/imatharray) - Новый экземпляр типа [IMathArray](../../com.aspose.slides/imatharray).
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Сохраняет содержимое этого [MathBlock](../../com.aspose.slides/mathblock) как MathML.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток. |