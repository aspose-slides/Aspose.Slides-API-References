---
title: Size
second_title: Aspose.Slides для Android через Java — справочник API
description: Класс для описания ширины и высоты в произвольных единицах.
type: docs
url: /ru/com.aspose.slides.android/size/
---
**Наследование:**
java.lang.Object
```
public class Size
```

Класс для описания ширины и высоты в произвольных единицах.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Создать новый экземпляр Size. |
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Получить ширину размера. |
| [getHeight()](#getHeight--) | Получить высоту размера. |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверить, равен ли этот размер другому размеру. |
| [hashCode()](#hashCode--) | {@inheritDoc} |
| [toString()](#toString--) | Вернуть размер в виде строки формата "WxH" |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

Создать новый экземпляр Size.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина размера |
| height | int | Высота размера |

### getWidth() {#getWidth--}
```
public int getWidth()
```

Получить ширину размера.

**Возвращаемое значение:**
int - ширина
### getHeight() {#getHeight--}
```
public int getHeight()
```

Получить высоту размера.

**Возвращаемое значение:**
int - высота
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Проверить, равен ли этот размер другому размеру.

Два размера равны тогда и только тогда, когда их ширины и высоты равны.

Объект размера никогда не равен объекту другого типа.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Возвращаемое значение:**
boolean - true если объекты равны, false в противном случае
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

Вернуть размер в виде строки формата "WxH"

**Возвращаемое значение:**
java.lang.String - строковое представление размера