---
title: IConnector
second_title: Справочник API Aspose.Slides для Java
description: Представляет соединитель.
type: docs
url: /ru/com.aspose.slides/iconnector/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Представляет connector.
## Методы

| Метод | Описание |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Возвращает блокировки shape. |
| [getConnectorLock()](#getConnectorLock--) | Возвращает блокировки Connector. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Возвращает или задает shape, к которому прикрепляется начало connector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Возвращает или задает shape, к которому прикрепляется начало connector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Возвращает или задает shape, к которому прикрепляется конец connector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Возвращает или задает shape, к которому прикрепляется конец connector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Возвращает или задает индекс точки подключения для start shape. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Возвращает или задает индекс точки подключения для start shape. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Возвращает или задает индекс точки подключения для end shape. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Возвращает или задает индекс точки подключения для end shape. |
| [reroute()](#reroute--) | Перенаправляет connector так, чтобы он проходил по кратчайшему возможному пути между shape, которые он соединяет. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

Возвращает блокировки shape. Только для чтения [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Возвращаемое значение:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Возвращает блокировки Connector. Только для чтения [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Возвращаемое значение:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

Возвращает или задает shape, к которому прикрепляется начало connector. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

Возвращает или задает shape, к которому прикрепляется начало connector. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

Возвращает или задает shape, к которому прикрепляется конец connector. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

Возвращает или задает shape, к которому прикрепляется конец connector. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

Возвращает или задает индекс точки подключения для start shape. Чтение/запись long.

**Возвращаемое значение:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

Возвращает или задает индекс точки подключения для start shape. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

Возвращает или задает индекс точки подключения для end shape. Чтение/запись long.

**Возвращаемое значение:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

Возвращает или задает индекс точки подключения для end shape. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

Перенаправляет connector так, чтобы он проходил по кратчайшему возможному пути между shape, которые он соединяет.