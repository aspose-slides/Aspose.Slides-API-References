---
title: IsVisible()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 점이 현재 객체가 나타내는 영역에 포함되어 있는지 확인합니다.
type: docs
weight: 196
url: /ko/system.drawing/region/isvisible/
---
## Region::IsVisible(const Point\&) const 메서드

지정된 점이 현재 객체가 나타내는 영역에 포함되어 있는지 확인합니다.

```cpp
bool System::Drawing::Region::IsVisible(const Point &point) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | const [Point](../../point/)\& | 검사할 점 |

## Region::IsVisible(const PointF\&) const 메서드

지정된 점이 현재 객체가 나타내는 영역에 포함되어 있는지 확인합니다.

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | 검사할 점 |

## Region::IsVisible(const Rectangle\&) 메서드

지정된 사각형의 일부가 현재 객체가 나타내는 영역에 포함되어 있는지 확인합니다.

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 검사할 사각형 |

## Region::IsVisible(const RectangleF\&) 메서드

지정된 사각형의 일부가 현재 객체가 나타내는 영역에 포함되어 있는지 확인합니다.

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 검사할 사각형 |

## Region::IsVisible(const Point\&, const SharedPtr\<Graphics\>\&) const 메서드

지정된 그래픽을 사용하여 지정된 점이 현재 객체가 나타내는 영역에 포함되어 있는지 확인합니다.

```cpp
bool System::Drawing::Region::IsVisible(const Point &point, const SharedPtr<Graphics> &graphics) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | const [Point](../../point/)\& | 검사할 점 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 그래픽 컨텍스트 |

## Region::IsVisible(const PointF\&, const SharedPtr\<Graphics\>\&) const 메서드

지정된 그래픽을 사용하여 지정된 점이 현재 객체가 나타내는 영역에 포함되어 있는지 확인합니다.

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point, const SharedPtr<Graphics> &graphics) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | 검사할 점 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 그래픽 컨텍스트 |

## Region::IsVisible(const Rectangle\&, const SharedPtr\<Graphics\>\&) 메서드

지정된 그래픽을 사용하여 지정된 사각형의 일부가 현재 객체가 나타내는 영역에 포함되어 있는지 확인합니다.

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect, const SharedPtr<Graphics> &graphics)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 검사할 사각형 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 그래픽 컨텍스트 |

## Region::IsVisible(const RectangleF\&, const SharedPtr\<Graphics\>\&) 메서드

지정된 그래픽을 사용하여 지정된 사각형의 일부가 현재 객체가 나타내는 영역에 포함되어 있는지 확인합니다.

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect, const SharedPtr<Graphics> &graphics)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 검사할 사각형 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 그래픽 컨텍스트 |

## Region::IsVisible(float, float) const 메서드

지정된 점이 현재 객체가 나타내는 영역에 포함되어 있는지 확인합니다.

```cpp
bool System::Drawing::Region::IsVisible(float x, float y) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 검사할 점의 X 좌표 |
| y | **float** | 검사할 점의 Y 좌표 |

## Region::IsVisible(float, float, const SharedPtr\<Graphics\>\&) const 메서드

지정된 그래픽을 사용하여 지정된 점이 현재 객체가 나타내는 영역에 포함되어 있는지 확인합니다.

```cpp
bool System::Drawing::Region::IsVisible(float x, float y, const SharedPtr<Graphics> &graphics) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 검사할 점의 X 좌표 |
| y | **float** | 검사할 점의 Y 좌표 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 그래픽 컨텍스트 |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Point](../../point/)
* 클래스 [Region](../)
* 클래스 [PointF](../../pointf/)
* 클래스 [Rectangle](../../rectangle/)
* 클래스 [RectangleF](../../rectanglef/)
* 클래스 [Graphics](../../graphics/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)