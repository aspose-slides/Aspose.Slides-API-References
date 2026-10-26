---
title: GeometryPath
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: GeometryShape의 기하학 경로를 나타냅니다
type: docs
url: /ko/com.aspose.slides/geometrypath/
---
**상속:**  
java.lang.Object

**모든 구현된 인터페이스:**  
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)  
```
public final class GeometryPath implements IGeometryPath
```

GeometryShape의 기하학 경로를 나타냅니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | GeometryPath 인스턴스를 생성합니다 |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPathData()](#getPathData--) | GeometryShape의 기하학 경로를 경로 세그먼트 배열로 반환합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에서 기하학 경로의 세그먼트를 제거합니다. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | 경로 끝에 선을 추가합니다. |
| [lineTo(float x, float y)](#lineTo-float-float-) | 경로 끝에 선을 추가합니다. |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | 경로의 지정된 위치에 선을 추가합니다. |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | 경로의 지정된 위치에 선을 추가합니다. |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | 경로 끝에 3차 베지어 곡선을 추가합니다. |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | 경로 끝에 3차 베지어 곡선을 추가합니다. |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | 경로의 지정된 위치에 3차 베지어 곡선을 추가합니다. |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | 경로의 지정된 위치에 3차 베지어 곡선을 추가합니다. |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | 경로 끝에 2차 베지어 곡선을 추가합니다. |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | 경로 끝에 2차 베지어 곡선을 추가합니다. |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | 경로의 지정된 위치에 2차 베지어 곡선을 추가합니다. |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | 경로의 지정된 위치에 2차 베지어 곡선을 추가합니다. |
| [closeFigure()](#closeFigure--) | 현재 경로의 도형을 닫습니다. |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | 다음 점 위치를 설정합니다. |
| [moveTo(float x, float y)](#moveTo-float-float-) | 다음 점 위치를 설정합니다. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | 지정된 호를 경로에 추가합니다. |
| [getFillMode()](#getFillMode--) | 채우기 모드를 설정합니다. |
| [setFillMode(byte value)](#setFillMode-byte-) | 채우기 모드를 설정합니다. |
| [getStroke()](#getStroke--) | 스트로크 모양을 설정합니다. |
| [setStroke(boolean value)](#setStroke-boolean-) | 스트로크 모양을 설정합니다. |

### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

GeometryPath 인스턴스를 생성합니다

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

GeometryShape의 기하학 경로를 경로 세그먼트 배열로 반환합니다.

**반환값:**  
com.aspose.slides.IPathSegment[]

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스에서 기하학 경로의 세그먼트를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삭제해야 하는 기하학 경로의 인덱스. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

경로 끝에 선을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point | android.graphics.PointF | 선의 끝점 |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

경로 끝에 선을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 선 끝점의 X 좌표 |
| y | float | 선 끝점의 Y 좌표 |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

경로의 지정된 위치에 선을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point | android.graphics.PointF | 끝점 |
| index | long | PathData 내 세그먼트 인덱스 |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

경로의 지정된 위치에 선을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 점의 X 좌표 |
| y | float | 점의 Y 좌표 |
| index | long | PathData 내 세그먼트 인덱스 |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

경로 끝에 3차 베지어 곡선을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 첫 번째 방향점 |
| point2 | android.graphics.PointF | 두 번째 방향점 |
| point3 | android.graphics.PointF | 끝점 |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

경로 끝에 3차 베지어 곡선을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x1 | float | 첫 번째 방향점의 X 좌표 |
| y1 | float | 첫 번째 방향점의 Y 좌표 |
| x2 | float | 두 번째 방향점의 X 좌표 |
| y2 | float | 두 번째 방향점의 Y 좌표 |
| x3 | float | 끝점의 X 좌표 |
| y3 | float | 끝점의 Y 좌표 |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

경로의 지정된 위치에 3차 베지어 곡선을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 첫 번째 방향점 |
| point2 | android.graphics.PointF | 두 번째 방향점 |
| point3 | android.graphics.PointF | 끝점 |
| index | long | PathData 내 세그먼트 인덱스 |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

경로의 지정된 위치에 3차 베지어 곡선을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x1 | float | 첫 번째 방향점의 X 좌표 |
| y1 | float | 첫 번째 방향점의 Y 좌표 |
| x2 | float | 두 번째 방향점의 X 좌표 |
| y2 | float | 두 번째 방향점의 Y 좌표 |
| x3 | float | 끝점의 X 좌표 |
| y3 | float | 끝점의 Y 좌표 |
| index | long | PathData 내 세그먼트 인덱스 |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

경로 끝에 2차 베지어 곡선을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 방향점 |
| point2 | android.graphics.PointF | 끝점 |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

경로 끝에 2차 베지어 곡선을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x1 | float | 방향점의 X 좌표 |
| y1 | float | 방향점의 Y 좌표 |
| x2 | float | 끝점의 X 좌표 |
| y2 | float | 끝점의 Y 좌표 |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

경로의 지정된 위치에 2차 베지어 곡선을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 방향점 |
| point2 | android.graphics.PointF | 끝점 |
| index | long | PathData 내 세그먼트 인덱스 |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

경로의 지정된 위치에 2차 베지어 곡선을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x1 | float | 방향점의 X 좌표 |
| y1 | float | 방향점의 Y 좌표 |
| x2 | float | 끝점의 X 좌표 |
| y2 | float | 끝점의 Y 좌표 |
| index | long | PathData 내 세그먼트 인덱스 |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

현재 경로의 도형을 닫습니다.

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

다음 점 위치를 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point | android.graphics.PointF | 점 위치 |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

다음 점 위치를 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 점의 X 좌표 |
| y | float | 점의 Y 좌표 |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

지정된 호를 경로에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| width | float | 사각형의 너비 |
| heigth | float | 사각형의 높이 |
| startAngle | float | 시작 각도 |
| sweepAngle | float | 스윕 각도 |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

채우기 모드를 설정합니다.

**반환값:**  
byte

### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

채우기 모드를 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

스트로크 모양을 설정합니다.

**반환값:**  
boolean

### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

스트로크 모양을 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |