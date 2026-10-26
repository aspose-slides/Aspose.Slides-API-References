---
title: TabCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию табов.
type: docs
url: /ru/com.aspose.slides/tabcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Представляет коллекцию табов.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает фактическое количество элементов, содержащихся в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [add(double position, int align)](#add-double-int-) | Добавляет Tab в коллекцию. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Добавляет Tab в коллекцию. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу в коллекции. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равны ли два экземпляра TabsEx. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает корень синхронизации. |

### size() {#size--}
```
public final int size()
```

Возвращает фактическое количество элементов, содержащихся в коллекции. Только для чтения int.

**Возвращает:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

Возвращает элемент по указанному индексу. Только для чтения [Tab](../../com.aspose.slides/tab).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[ITab](../../com.aspose.slides/itab)

### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

Добавляет Tab в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Возвращает:**
[ITab](../../com.aspose.slides/itab) - Добавленная вкладка.

### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

Добавляет Tab в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Объект Tab, который будет добавлен в конец коллекции. |

**Возвращает:**
int - Индекс, по которому была добавлена вкладка.

### clear() {#clear--}
```
public final void clear()
```

Удаляет все элементы из коллекции.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет элемент по указанному индексу в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой базовый индекс элемента, который нужно удалить. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равны ли два экземпляра TabsEx.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | TabsEx для сравнения с текущим TabsEx. |

**Возвращает:**
boolean - **true** если указанный TabsEx равен текущему TabsEx; в противном случае **false**.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - An java.util.Iterator for the entire collection.

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

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). Только для чтения boolean.

**Возвращает:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает корень синхронизации. Только для чтения Object.

**Возвращает:**
java.lang.Object