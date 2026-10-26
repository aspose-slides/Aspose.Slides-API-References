---
title: ParagraphCollection
second_title: Aspose.Slides для Android через Java API Reference
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
| [getCount()](#getCount--) | Возвращает количество элементов, фактически содержащихся в коллекции. |
| [isReadOnly()](#isReadOnly--) | Возвращает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Добавляет Paragraph в конец коллекции. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Добавляет содержимое ParagraphCollection в конец коллекции. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Определяет индекс конкретного элемента в List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Вставляет Paragraph в коллекцию по указанному индексу. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Вставляет содержимое ParagraphCollection в коллекцию по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с определённого индекса массива. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу из коллекции. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Удаляет первое вхождение конкретного объекта из [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
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


Возвращает количество элементов, фактически содержащихся в коллекции. Толькочтение int.

**Возвращает:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Возвращает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. Толькочтение boolean.

**Возвращает:**
boolean — true, если [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения; в противном случае — false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```


Возвращает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
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

**Возвращает:**
int — индекс, по которому был добавлен Paragraph, или -1, если нечего добавлять.
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```


Определяет индекс конкретного элемента в List.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Объект для поиска в List. |

**Возвращает:**
int — индекс элемента, если он найден в списке; в противном случае — -1.
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
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Объект для поиска в [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращает:**
boolean — true, если элемент найден в [IGenericCollection](../../com.aspose.slides/igenericcollection); в противном случае — false.
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```


Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с определённого индекса массива.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Одномерный массив, в который копируются элементы из [IGenericCollection](../../com.aspose.slides/igenericcollection). Массив должен иметь нулевую базу индекса. |
| arrayIndex | int | Нулевой индекс в массиве, с которого начинается копирование. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Удаляет элемент по указанному индексу из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который следует удалить. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```


Удаляет первое вхождение конкретного объекта из [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Объект для удаления из [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращает:**
boolean — true, если элемент был успешно удалён из [IGenericCollection](../../com.aspose.slides/igenericcollection); в противном случае — false. Этот метод также возвращает false, если элемент не найден в оригинальном [IGenericCollection](../../com.aspose.slides/igenericcollection).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```


Возвращает перечислитель, который проходит по коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - перечислитель, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - java.util.Iterator для всей коллекции.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Возвращает родительский слайд коллекции абзацев. Толькочтение [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращает:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Возвращает родительскую презентацию коллекции абзацев. Толькочтение [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращает:**
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

Указание resolver может потенциально привести к уязвимости. Используйте с осторожностью. | 

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


Преобразует указанные абзацы в HTML и возвращает его как объект String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstParagraphIndex | int | First paragraph index int |
| paragraphsCount | int | Paragraph count int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Convert options [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Возвращает:**
java.lang.String - Generated HTML.