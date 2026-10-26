---
title: IConnector
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет соединитель.
type: docs
url: /ru/com.aspose.slides/iconnector/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Представляет соединитель.
## Методы

| Method | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Возвращает блокировки фигуры. |
| [getConnectorLock()](#getConnectorLock--) | Возвращает блокировки соединителя. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Возвращает или задает фигуру, к которой прикрепляется начало соединителя. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Возвращает или задает фигуру, к которой прикрепляется начало соединителя. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Возвращает или задает фигуру, к которой прикрепляется конец соединителя. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Возвращает или задает фигуру, к которой прикрепляется конец соединителя. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Возвращает или задает индекс места соединения для начальной фигуры. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Возвращает или задает индекс места соединения для начальной фигуры. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Возвращает или задает индекс места соединения для конечной фигуры. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Возвращает или задает индекс места соединения для конечной фигуры. |
| [reroute()](#reroute--) | Перенаправляет соединитель так, чтобы он проходил по кратчайшему возможному пути между фигурами, которые он соединяет. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

Возвращает блокировки фигуры. Только для чтения [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Возвращает:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Возвращает блокировки соединителя. Только для чтения [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Возвращает:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

Возвращает или задает фигуру, к которой прикрепляется начало соединителя. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Возвращает:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

Возвращает или задает фигуру, к которой прикрепляется начало соединителя. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

Возвращает или задает фигуру, к которой прикрепляется конец соединителя. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Возвращает:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

Возвращает или задает фигуру, к которой прикрепляется конец соединителя. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

Возвращает или задает индекс места соединения для начальной фигуры. Чтение/запись long.

**Возвращает:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

Возвращает или задает индекс места соединения для начальной фигуры. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

Возвращает или задает индекс места соединения для конечной фигуры. Чтение/запись long.

**Возвращает:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

Возвращает или задает индекс места соединения для конечной фигуры. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

Перенаправляет соединитель так, чтобы он следовал по кратчайшему возможному пути между фигурами, которые он соединяет.