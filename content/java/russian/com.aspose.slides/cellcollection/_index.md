---
title: CellCollection
second_title: Aspose.Slides для Java справочник API
description: Представляет коллекцию ячеек.
type: docs
url: /ru/com.aspose.slides/cellcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

Представляет коллекцию ячеек.
## Методы

| Метод | Описание |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Возвращает количество ячеек в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает ячейку по её позиции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд CellCollection. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию CellCollection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект-корень синхронизации. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```

Возвращает количество ячеек в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

Возвращает ячейку по её позиции. Только для чтения [Cell](../../com.aspose.slides/cell).

--------------------

Один объект Cell может быть возвращён для нескольких индексов, если ячейка объединена.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Перечислитель IGenericEnumerator, который может использоваться для прохода по коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - java.util.Iterator для всей коллекции.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд CellCollection. Только для чтения [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию CellCollection. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект-корень синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object