---
title: ParagraphCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию абзацев.
type: docs
url: /ru/com.aspose.slides/paragraphcollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Представляет коллекцию абзацев.
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Получает количество элементов, фактически содержащихся в коллекции. |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Добавляет Paragraph в конец коллекции. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Добавляет содержимое ParagraphCollection в конец коллекции. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Определяет индекс конкретного элемента в списке. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Вставляет Paragraph в коллекцию по указанному индексу. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Вставляет содержимое ParagraphCollection в коллекцию по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с определённого индекса массива. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу из коллекции. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Удаляет первое вхождение конкретного объекта из [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд коллекции абзацев. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию коллекции абзацев. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Добавляет текст из указанной HTML-строки в коллекцию. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Добавляет текст из указанной HTML-строки в коллекцию. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Преобразует указанные абзацы в HTML и возвращает его как объект String. |

### getCount() {#getCount--}
```
public final int getCount()
```

Получает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

**Возвращаемое значение:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Получает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. Только для чтения boolean.

**Возвращаемое значение:**
boolean - true, если [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения; иначе false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Получает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Добавляет Paragraph в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph, который будет добавлен в конец коллекции. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

Добавляет содержимое ParagraphCollection в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection, который будет добавлен в конец коллекции. |

**Возвращаемое значение:**
int - Индекс, по которому Paragraph был добавлен, или -1, если нечего добавлять.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Определяет индекс конкретного элемента в List.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Объект, который требуется найти в List. |

**Возвращаемое значение:**
int - Индекс элемента, если он найден в списке; иначе -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Вставляет Paragraph в коллекцию по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому следует вставить Paragraph. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph для вставки. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Вставляет содержимое ParagraphCollection в коллекцию по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому следует вставить абзацы. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Абзацы для вставки. |

### clear() {#clear--}
```
public final void clear()
```

Удаляет все элементы из коллекции.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Объект, который требуется найти в [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращаемое значение:**
boolean - true, если элемент найден в [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с определённого индекса массива.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Одномерный массив, который является получателем элементов, скопированных из [IGenericCollection](../../com.aspose.slides/igenericcollection). Массив должен использовать нулевую индексацию. |
| arrayIndex | int | Нулевой индекс в массиве, с которого начинается копирование. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет элемент по указанному индексу из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который нужно удалить. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Удаляет первое вхождение конкретного объекта из [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Объект, который следует удалить из [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращаемое значение:**
boolean - true, если элемент был успешно удалён из [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false. Этот метод также возвращает false, если элемент не найден в оригинальном [IGenericCollection](../../com.aspose.slides/igenericcollection).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - IGenericEnumerator, который можно использовать для перебора элементов коллекции.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - java.util.Iterator для всей коллекции.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд коллекции абзацев. Только для чтения [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию коллекции абзацев. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Добавляет текст из указанной HTML-строки в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | HTML-текст. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Добавляет текст из указанной HTML-строки в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | HTML-текст. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект обратного вызова Resolver, который разрешает URI и получает связанные объекты. |
| uri | java.lang.String | URI для добавления HTML-документа. Используется для разрешения относительных ссылок. |

--------------------
Указание resolver может потенциально привести к уязвимости. Используйте с осторожностью.

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Преобразует указанные абзацы в HTML и возвращает его как объект String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstParagraphIndex | int | Индекс первого абзаца int |
| paragraphsCount | int | Количество абзацев int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Параметры конвертации [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Возвращаемое значение:**
java.lang.String - Сгенерированный HTML.