---
title: Connector
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 커넥터를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/connector/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

커넥터를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | 모양의 잠금을 반환합니다. |
| [getConnectorLock()](#getConnectorLock--) | 커넥터의 잠금을 반환합니다. |
| [getShapeType()](#getShapeType--) | AutoShape 유형을 반환하거나 설정합니다. |
| [setShapeType(int value)](#setShapeType-int-) | AutoShape 유형을 반환하거나 설정합니다. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | 커넥터 시작을 연결할 모양을 반환하거나 설정합니다. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | 커넥터 시작을 연결할 모양을 반환하거나 설정합니다. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | 커넥터 끝을 연결할 모양을 반환하거나 설정합니다. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | 커넥터 끝을 연결할 모양을 반환하거나 설정합니다. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | 시작 모양에 대한 연결 지점 인덱스를 반환하거나 설정합니다. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | 시작 모양에 대한 연결 지점 인덱스를 반환하거나 설정합니다. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | 끝 모양에 대한 연결 지점 인덱스를 반환하거나 설정합니다. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | 끝 모양에 대한 연결 지점 인덱스를 반환하거나 설정합니다. |
| [reroute()](#reroute--) | 연결된 모양 사이의 최단 경로를 사용하도록 커넥터를 재경로합니다. |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

모양의 잠금을 반환합니다. 읽기 전용 [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**반환:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

커넥터의 잠금을 반환합니다. 읽기 전용 [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**반환:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

AutoShape 유형을 반환하거나 설정합니다. 읽기/쓰기 [ShapeType](../../com.aspose.slides/shapetype).

**반환:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

AutoShape 유형을 반환하거나 설정합니다. 읽기/쓰기 [ShapeType](../../com.aspose.slides/shapetype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

커넥터 시작을 연결할 모양을 반환하거나 설정합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**반환:**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

커넥터 시작을 연결할 모양을 반환하거나 설정합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

커넥터 끝을 연결할 모양을 반환하거나 설정합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**반환:**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

커넥터 끝을 연결할 모양을 반환하거나 설정합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

시작 모양에 대한 연결 지점 인덱스를 반환하거나 설정합니다. 읽기/쓰기 long.

**반환:**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

시작 모양에 대한 연결 지점 인덱스를 반환하거나 설정합니다. 읽기/쓰기 long.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

끝 모양에 대한 연결 지점 인덱스를 반환하거나 설정합니다. 읽기/쓰기 long.

**반환:**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

끝 모양에 대한 연결 지점 인덱스를 반환하거나 설정합니다. 읽기/쓰기 long.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

연결된 모양 사이의 최단 경로를 사용하도록 커넥터를 재경로합니다.