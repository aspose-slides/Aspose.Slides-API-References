---
title: ColorOperation
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет различные операции над цветом, используемые для цветовых преобразований.
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

Представляет различные операции над цветом, используемые для цветовых преобразований. Неизменяемый объект.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Создаёт новую операцию преобразования цвета. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Создаёт новую операцию преобразования цвета. |
## Методы

| Метод | Описание |
| --- | --- |
| [getOperationType()](#getOperationType--) | Возвращает или задаёт тип операции. |
| [getParameter()](#getParameter--) | Возвращает параметр операции. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равны ли два экземпляра ColorOperation. |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа, подходящей для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```


Создаёт новую операцию преобразования цвета.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| op | int | Тип операции. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```


Создаёт новую операцию преобразования цвета.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| op | int | Тип операции. |
| parameter | float | Параметр операции. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```


Возвращает или задаёт тип операции. Только для чтения [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Возвращаемое значение:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```


Возвращает параметр операции. Только для чтения float.

**Возвращаемое значение:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равны ли два экземпляра ColorOperation.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Экземпляр ColorOperation, с которым сравнивается текущий ColorOperation. |

**Возвращаемое значение:**
boolean - **true** если указанный ColorOperation равен текущему ColorOperation; иначе **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит хеш-функцией для конкретного типа, подходящей для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.

**Возвращаемое значение:**
int