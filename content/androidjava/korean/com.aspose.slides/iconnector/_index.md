---
title: IConnector
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 커넥터를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iconnector/
---
**모든 구현된 인터페이스:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

커넥터를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | shape의 잠금을 반환합니다. |
| [getConnectorLock()](#getConnectorLock--) | Connector의 잠금을 반환합니다. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | 시작점에 연결할 shape를 반환하거나 설정합니다. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | 시작점에 연결할 shape를 반환하거나 설정합니다. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | 끝점에 연결할 shape를 반환하거나 설정합니다. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | 끝점에 연결할 shape를 반환하거나 설정합니다. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | 시작 shape의 연결 사이트 인덱스를 반환하거나 설정합니다. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | 시작 shape의 연결 사이트 인덱스를 반환하거나 설정합니다. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | 끝 shape의 연결 사이트 인덱스를 반환하거나 설정합니다. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | 끝 shape의 연결 사이트 인덱스를 반환하거나 설정합니다. |
| [reroute()](#reroute--) | connector를 재경로하여 연결된 shape 사이의 가능한 가장 짧은 경로를 취하도록 합니다. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

shape의 잠금을 반환합니다. 읽기 전용 [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**반환값:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Connector의 잠금을 반환합니다. 읽기 전용 [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**반환값:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

시작점에 연결할 shape를 반환하거나 설정합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**반환값:**  
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

시작점에 연결할 shape를 반환하거나 설정합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

끝점에 연결할 shape를 반환하거나 설정합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**반환값:**  
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

끝점에 연결할 shape를 반환하거나 설정합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

시작 shape의 연결 사이트 인덱스를 반환하거나 설정합니다. 읽기/쓰기 long.

**반환값:**  
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

시작 shape의 연결 사이트 인덱스를 반환하거나 설정합니다. 읽기/쓰기 long.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

끝 shape의 연결 사이트 인덱스를 반환하거나 설정합니다. 읽기/쓰기 long.

**반환값:**  
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

끝 shape의 연결 사이트 인덱스를 반환하거나 설정합니다. 읽기/쓰기 long.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

connector를 재경로하여 연결된 shape 사이의 가능한 가장 짧은 경로를 취하도록 합니다.