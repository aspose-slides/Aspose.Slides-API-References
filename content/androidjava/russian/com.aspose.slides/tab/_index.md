---
title: Tab
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет табуляцию для текста.
type: docs
url: /ru/com.aspose.slides/tab/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Представляет табуляцию для текста.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Создает новый Tab |
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Возвращает или задает позицию табуляции. |
| [setPosition(double value)](#setPosition-double-) | Возвращает или задает позицию табуляции. |
| [getAlignment()](#getAlignment--) | Возвращает или задает стиль выравнивания табуляции. |
| [setAlignment(int value)](#setAlignment-int-) | Возвращает или задает стиль выравнивания табуляции. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Сравнивает текущий экземпляр с другим объектом того же типа. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```


Создает новый Tab

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | double | Позиция табуляции. |
| align | int | Выравнивание. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Версия. Только для чтения long.

**Возвращаемое значение:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```


Возвращает или задает позицию табуляции. Присваивание этого свойства может изменить индекс табуляции в коллекции и сделать недействительным Enumerator. Чтение/запись double.

**Возвращаемое значение:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```


Возвращает или задает позицию табуляции. Присваивание этого свойства может изменить индекс табуляции в коллекции и сделать недействительным Enumerator. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Возвращает или задает стиль выравнивания табуляции. Чтение/запись [TabAlignment](../../com.aspose.slides/tabalignment).

**Возвращаемое значение:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Возвращает или задает стиль выравнивания табуляции. Чтение/запись [TabAlignment](../../com.aspose.slides/tabalignment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Сравнивает текущий экземпляр с другим объектом того же типа.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с этим экземпляром. |

**Возвращаемое значение:**
int - 32-битное целое, указывающее относительный порядок сравниваемых объектов. Возвращаемое значение имеет следующие значения: 

 *  < 0 - Этот экземпляр меньше obj.
 *  = 0 - Этот экземпляр равен obj.
 *  > 0 - Этот экземпляр больше obj.