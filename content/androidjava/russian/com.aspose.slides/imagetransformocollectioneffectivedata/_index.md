---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides для Android через справочник Java API
description: Неизменяемый объект, представляющий только для чтения коллекцию эффективных эффектов преобразования изображений.
type: docs
url: /ru/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

Неизменяемый объект, представляющий только для чтения коллекцию эффективных эффектов преобразования изображений.

--------------------

Имя IImageTransformOperationCollectionEffectiveData сокращено до IImageTransformOCollectionEffectiveData из-за ограничения длины имён COM, которое не может превышать 39.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество эффектов изображения в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по индексу. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный объект текущему объекту. |
| [hashCode()](#hashCode--) | Служит в качестве хеш-функции для определённого типа, подходящей для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```


### size() {#size--}
```
public final int size()
```


Возвращает количество эффектов изображения в коллекции. Только для чтения int.

**Возвращает:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```


Возвращает элемент по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента. |

**Возвращает:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - Объект [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный объект текущему объекту.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с текущим объектом. |

**Возвращает:**
boolean — true, если указанный объект равен текущему объекту; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит в качестве хеш-функции для определённого типа, подходящей для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.

**Возвращает:**
int — Хеш-код текущего объекта.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```


Возвращает перечислитель, который перебирает коллекцию.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - java.util.Iterator для всей коллекции.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Массив для заполнения. |
| index | int | Начальная позиция в целевом массиве. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения boolean.

**Возвращает:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Возвращает объект синхронизации. Только для чтения Object.

**Возвращает:**
java.lang.Object