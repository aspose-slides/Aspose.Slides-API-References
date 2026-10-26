---
title: SizeF
second_title: Aspose.Slides для Android через справочник API Java
description: Класс для описания размеров ширины и высоты в произвольных единицах с плавающей точкой.
type: docs
url: /ru/com.aspose.slides.android/sizef/
---
**Наследование:**
java.lang.Object
```
public class SizeF
```

Класс для описания размеров ширины и высоты в произвольных единицах с плавающей точкой.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Создать новый экземпляр SizeF. |
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Получить ширину размера. |
| [getHeight()](#getHeight--) | Получить высоту размера. |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверить, равен ли этот размер другому размеру. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Возвратить размер в виде строки формата "WxH" |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

Создать новый экземпляр SizeF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | float | Ширина размера |
| height | float | Высота размера |

### getWidth() {#getWidth--}
```
public float getWidth()
```

Получить ширину размера.

**Возвращаемое значение:**
float - ширина
### getHeight() {#getHeight--}
```
public float getHeight()
```

Получить высоту размера.

**Возвращаемое значение:**
float - высота
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Проверить, равен ли этот размер другому размеру.

Два размера равны тогда и только тогда, когда их ширины и высоты одинаковы.

Для этой цели значения float ширины/высоты считаются одинаковыми тогда и только тогда, когда метод Float#floatToIntBits(float).floatToIntBits(float) возвращает идентичное значение int при применении к каждому.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Возвращаемое значение:**
boolean - true если объекты были равны, false в противном случае
### hashCode() {#hashCode--}
```
public int hashCode()
```

**Возвращаемое значение:**
int
### toString() {#toString--}
```
public String toString()
```

Возвратить размер в виде строки формата "WxH"

**Возвращаемое значение:**
java.lang.String - строковое представление размера