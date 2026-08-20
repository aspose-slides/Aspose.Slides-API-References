---
title: GeometryPath
second_title: Aspose.Slides for Java API 레퍼런스
description: GeometryShape의 기하학적 경로를 나타냅니다
type: docs
url: /ko/com.aspose.slides/geometrypath/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

GeometryShape의 geometry path를 나타냅니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | GeometryPath의 인스턴스를 생성합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPathData()](#getPathData--) | GeometryShape의 geometry path를 경로 세그먼트 배열로 반환합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 geometry path 세그먼트를 제거합니다. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | 경로 끝에 선을 추가합니다 |
| [lineTo(float x, float y)](#lineTo-float-float-) | 경로 끝에 선을 추가합니다 |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | 경로의 지정된 위치에 선을 추가합니다 |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | 경로의 지정된 위치에 선을 추가합니다 |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | 경로 끝에 큐빅 베지어 곡선을 추가합니다 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | 경로 끝에 큐빅 베지어 곡선을 추가합니다 |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | 경로의 지정된 위치에 큐빅 베지어 곡선을 추가합니다 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | 경로의 지정된 위치에 큐빅 베지어 곡선을 추가합니다 |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | 경로 끝에 쿼드러틱 베지어 곡선을 추가합니다 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | 경로 끝에 쿼드러틱 베지어 곡선을 추가합니다 |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | 경로의 지정된 위치에 쿼드러틱 베지어 곡선을 추가합니다 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | 경로의 지정된 위치에 쿼드러틱 베지어 곡선을 추가합니다 |
| [closeFigure()](#closeFigure--) | 이 경로의 현재 도형을 닫습니다 |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | 다음 점 위치를 설정합니다. |
| [moveTo(float x, float y)](#moveTo-float-float-) | 다음 점 위치를 설정합니다. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | 지정된 호를 경로에 추가합니다. |
| [getFillMode()](#getFillMode--) | 채우기 모드를 설정합니다 |
| [setFillMode(byte value)](#setFillMode-byte-) | 채우기 모드를 설정합니다 |
| [getStroke()](#getStroke--) | 스트로크 모양을 설정합니다 |
| [setStroke(boolean value)](#setStroke-boolean-) | 스트로크 모양을 설정합니다 |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

GeometryPath의 인스턴스를 생성합니다

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

GeometryShape의 geometry path를 경로 세그먼트 배열로 반환합니다.

**반환값:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스의 geometry path 세그먼트를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 삭제해야 할 geometry path의 인덱스. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

경로 끝에 선을 추가합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 선의 끝점 |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

경로 끝에 선을 추가합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 선의 끝점 X 좌표 |
| y | float | 선의 끝점 Y 좌표 |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

경로의 지정된 위치에 선을 추가합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 끝점 |
| index | long | PathData 내 세그먼트 인덱스 |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

경로의 지정된 위치에 선을 추가합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 점의 X 좌표 |
| y | float | 점의 Y 좌표 |
| index | long | PathData 내 세그먼트 인덱스 |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

경로 끝에 큐빅 베지어 곡선을 추가합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 첫 번째 제어점 |
| point2 | java.awt.geom.Point2D.Float | 두 번째 제어점 |
| point3 | java.awt.geom.Point2D.Float | 끝점 |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

경로 끝에 큐빅 베지어 곡선을 추가합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x1 | float | 첫 번째 제어점의 X 좌표 |
| y1 | float | 첫 번째 제어점의 Y 좌표 |
| x2 | float | 두 번째 제어점의 X 좌표 |
| y2 | float | 두 번째 제어점의 Y 좌표 |
| x3 | float | 끝점의 X 좌표 |
| y3 | float | 끝점의 Y 좌표 |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

경로의 지정된 위치에 큐빅 베지어 곡선을 추가합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 첫 번째 제어점 |
| point2 | java.awt.geom.Point2D.Float | 두 번째 제어점 |
| point3 | java.awt.geom.Point2D.Float | 끝점 |
| index | long | PathData 내 세그먼트 인덱스 |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

경로의 지정된 위치에 큐빅 베지어 곡선을 추가합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x1 | float | 첫 번째 제어점의 X 좌표 |
| y1 | float | 첫 번째 제어점의 Y 좌표 |
| x2 | float | 두 번째 제어점의 X 좌표 |
| y2 | float | 두 번째 제어점의 Y 좌표 |
| x3 | float | 끝점의 X 좌표 |
| y3 | float | 끝점의 Y 좌표 |
| index | long | PathData 내 세그먼트 인덱스 |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

경로 끝에 쿼드러틱 베지어 곡선을 추가합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 제어점 |
| point2 | java.awt.geom.Point2D.Float | 끝점 |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

경로 끝에 쿼드러틱 베지어 곡선을 추가합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x1 | float | 제어점의 X 좌표 |
| y1 | float | 제어점의 Y 좌표 |
| x2 | float | 끝점의 X 좌표 |
| y2 | float | 끝점의 Y 좌표 |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

경로의 지정된 위치에 쿼드러틱 베지어 곡선을 추가합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 제어점 |
| point2 | java.awt.geom.Point2D.Float | 끝점 |
| index | long | PathData 내 세그먼트 인덱스 |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

경로의 지정된 위치에 쿼드러틱 베지어 곡선을 추가합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x1 | float | 제어점의 X 좌표 |
| y1 | float | 제어점의 Y 좌표 |
| x2 | float | 끝점의 X 좌표 |
| y2 | float | 끝점의 Y 좌표 |
| index | long | PathData 내 세그먼트 인덱스 |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

이 경로의 현재 도형을 닫습니다

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

다음 점 위치를 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 점 위치 |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

다음 점 위치를 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 점의 X 좌표 |
| y | float | 점의 Y 좌표 |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

지정된 호를 경로에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| width | float | 사각형의 너비 |
| heigth | float | 사각형의 높이 |
| startAngle | float | 시작 각도. |
| sweepAngle | float | 스윕 각도 |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

채우기 모드를 설정합니다

**반환값:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

채우기 모드를 설정합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

스트로크 모양을 설정합니다

**반환값:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

스트로크 모양을 설정합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |