---
title: Tab
second_title: Справочник API Aspose.Slides для Java
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
| [Tab(double position, int align)](#Tab-double-int-) | Создаёт новый Tab |
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Возвращает или задаёт позицию табуляции. |
| [setPosition(double value)](#setPosition-double-) | Возвращает или задаёт позицию табуляции. |
| [getAlignment()](#getAlignment--) | Возвращает или задаёт стиль выравнивания табуляции. |
| [setAlignment(int value)](#setAlignment-int-) | Возвращает или задаёт стиль выравнивания табуляции. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Сравнивает текущий экземпляр с другим объектом того же типа. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

Создаёт новый Tab

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

**Возвращает:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

Возвращает или задаёт позицию табуляции. Присвоение этого свойства может изменить индекс табуляции в коллекции и сделать недействительным Enumerator. Чтение/запись double.

**Возвращает:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Возвращает или задаёт позицию табуляции. Присвоение этого свойства может изменить индекс табуляции в коллекции и сделать недействительным Enumerator. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Возвращает или задаёт стиль выравнивания табуляции. Чтение/запись [TabAlignment](../../com.aspose.slides/tabalignment).

**Возвращает:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Возвращает или задаёт стиль выравнивания табуляции. Чтение/запись [TabAlignment](../../com.aspose.slides/tabalignment).

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

**Возвращает:**
int - 32-разрядное целое, указывающее относительный порядок сравниваемых объектов. Возвращаемое значение имеет следующие значения:

 *  < 0 - Этот экземпляр меньше obj.
 *  = 0 - Этот экземпляр равен obj.
 *  > 0 - Этот экземпляр больше obj.