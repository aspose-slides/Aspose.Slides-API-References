---
title: Connector
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет соединитель.
type: docs
url: /ru/com.aspose.slides/connector/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Все реализованные интерфейсы:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Представляет соединитель.
## Методы

| Метод | Описание |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Возвращает блокировки фигуры. |
| [getConnectorLock()](#getConnectorLock--) | Возвращает блокировки соединителя. |
| [getShapeType()](#getShapeType--) | Возвращает или задаёт тип AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | Возвращает или задаёт тип AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Возвращает или задаёт фигуру, к которой прикрепляется начало соединителя. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Возвращает или задаёт фигуру, к которой прикрепляется начало соединителя. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Возвращает или задаёт фигуру, к которой прикрепляется конец соединителя. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Возвращает или задаёт фигуру, к которой прикрепляется конец соединителя. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Возвращает или задаёт индекс точки подключения для начальной фигуры. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Возвращает или задаёт индекс точки подключения для начальной фигуры. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Возвращает или задаёт индекс точки подключения для конечной фигуры. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Возвращает или задаёт индекс точки подключения для конечной фигуры. |
| [reroute()](#reroute--) | Перенаправляет соединитель так, чтобы он выбирал кратчайший возможный путь между фигурами, которые он соединяет. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Возвращает блокировки фигуры. Только для чтения [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Возвращаемое значение:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

Возвращает блокировки соединителя. Только для чтения [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Возвращаемое значение:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Возвращает или задаёт тип AutoShape. Чтение/запись [ShapeType](../../com.aspose.slides/shapetype).

**Возвращаемое значение:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Возвращает или задаёт тип AutoShape. Чтение/запись [ShapeType](../../com.aspose.slides/shapetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Возвращает или задаёт фигуру, к которой прикрепляется начало соединителя. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Возвращает или задаёт фигуру, к которой прикрепляется начало соединителя. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Возвращает или задаёт фигуру, к которой прикрепляется конец соединителя. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Возвращает или задаёт фигуру, к которой прикрепляется конец соединителя. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Возвращает или задаёт индекс точки подключения для начальной фигуры. Чтение/запись long.

**Возвращаемое значение:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Возвращает или задаёт индекс точки подключения для начальной фигуры. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Возвращает или задаёт индекс точки подключения для конечной фигуры. Чтение/запись long.

**Возвращаемое значение:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

Возвращает или задаёт индекс точки подключения для конечной фигуры. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```

Перенаправляет соединитель так, чтобы он выбирал кратчайший возможный путь между фигурами, которые он соединяет.