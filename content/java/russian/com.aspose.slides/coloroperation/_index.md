---
title: ColorOperation
second_title: Aspose.Slides для Java API Справочник
description: Представляет различные операции над цветом, используемые для трансформаций цвета.
type: docs
url: /ru/com.aspose.slides/coloroperation/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Представляет различные операции над цветом, используемые для трансформаций цвета. Неизменяемый объект.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Создает новую операцию трансформации цвета. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Создает новую операцию трансформации цвета. |
## Методы

| Метод | Описание |
| --- | --- |
| [getOperationType()](#getOperationType--) | Возвращает или задает тип операции. |
| [getParameter()](#getParameter--) | Возвращает параметр операции. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равны ли два экземпляра ColorOperation. |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа, подходит для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```


Создает новую операцию трансформации цвета.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| op | int | Тип операции. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```


Создает новую операцию трансформации цвета.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| op | int | Тип операции. |
| parameter | float | Параметр операции. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```


Возвращает или задает тип операции. Только для чтения [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Возвращает:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```


Возвращает параметр операции. Только для чтения float.

**Возвращает:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равны ли два экземпляра ColorOperation.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект ColorOperation, с которым сравнивается текущий ColorOperation. |

**Возвращает:**
boolean - **true** если указанный ColorOperation равен текущему ColorOperation; в противном случае **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит хеш-функцией для конкретного типа, подходит для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.

**Возвращает:**
int