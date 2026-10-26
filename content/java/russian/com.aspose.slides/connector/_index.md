---
title: Connector
second_title: Справочник API Aspose.Slides для Java
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
| [getShapeLock()](#getShapeLock--) | Возвращает блокировки формы. |
| [getConnectorLock()](#getConnectorLock--) | Возвращает блокировки соединителя. |
| [getShapeType()](#getShapeType--) | Возвращает или задает тип AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | Возвращает или задает тип AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Возвращает или задает форму, к которой присоединяется начало соединителя. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Возвращает или задает форму, к которой присоединяется начало соединителя. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Возвращает или задает форму, к которой присоединяется конец соединителя. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Возвращает или задает форму, к которой присоединяется конец соединителя. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Возвращает или задает индекс места соединения для начальной формы. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Возвращает или задает индекс места соединения для начальной формы. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Возвращает или задает индекс места соединения для конечной формы. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Возвращает или задает индекс места соединения для конечной формы. |
| [reroute()](#reroute--) | Перенаправляет соединитель так, чтобы он следовал кратчайшему возможному пути между соединяемыми формами. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Возвращает блокировки формы. Только для чтения [IConnectorLock](../../com.aspose.slides/iconnectorlock).

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

Возвращает или задает тип AutoShape. Чтение/запись [ShapeType](../../com.aspose.slides/shapetype).

**Возвращаемое значение:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Возвращает или задает тип AutoShape. Чтение/запись [ShapeType](../../com.aspose.slides/shapetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Возвращает или задает форму, к которой присоединяется начало соединителя. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Возвращает или задает форму, к которой присоединяется начало соединителя. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Возвращает или задает форму, к которой присоединяется конец соединителя. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Возвращает или задает форму, к которой присоединяется конец соединителя. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Возвращает или задает индекс места соединения для начальной формы. Чтение/запись long.

**Возвращаемое значение:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Возвращает или задает индекс места соединения для начальной формы. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Возвращает или задает индекс места соединения для конечной формы. Чтение/запись long.

**Возвращаемое значение:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

Возвращает или задает индекс места соединения для конечной формы. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```

Перенаправляет соединитель так, чтобы он следовал кратчайшему возможному пути между соединяемыми формами.