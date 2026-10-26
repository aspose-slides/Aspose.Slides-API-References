---
title: FillRectangle()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 사각형을 지정된 브러시로 채웁니다.
type: docs
weight: 326
url: /ko/system.drawing/graphics/fillrectangle/
---
## Graphics::FillRectangle(const SharedPtr\<Brush\>\&, float, float, float, float) 메서드

지정된 사각형을 지정된 브러시로 채웁니다.

```cpp
void System::Drawing::Graphics::FillRectangle(const SharedPtr<Brush> &brush, float x, float y, float width, float height)
```

### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 채우는 데 사용할 [Brush](../../brush/) 객체 |
| x | **float** | 채울 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | **float** | 채울 사각형의 왼쪽 위 모서리의 Y 좌표 |
| width | **float** | 채울 사각형의 너비 |
| height | **float** | 채울 사각형의 높이 |

## Graphics::FillRectangle(const SharedPtr\<Brush\>\&, int, int, int, int) 메서드

지정된 사각형을 지정된 브러시로 채웁니다.

```cpp
void System::Drawing::Graphics::FillRectangle(const SharedPtr<Brush> &brush, int x, int y, int width, int height)
```

### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 채우는 데 사용할 [Brush](../../brush/) 객체 |
| x | int | 채울 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | int | 채울 사각형의 왼쪽 위 모서리의 Y 좌표 |
| width | int | 채울 사각형의 너비 |
| height | int | 채울 사각형의 높이 |

## Graphics::FillRectangle(const SharedPtr\<Brush\>\&, Rectangle) 메서드

지정된 사각형을 지정된 브러시로 채웁니다.

```cpp
void System::Drawing::Graphics::FillRectangle(const SharedPtr<Brush> &brush, Rectangle rect)
```

### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 채우는 데 사용할 [Brush](../../brush/) 객체 |
| rect | [Rectangle](../../rectangle/) | 채울 사각형의 위치와 크기를 지정하는 [Rectangle](../../rectangle/) 객체 |

## Graphics::FillRectangle(const SharedPtr\<Brush\>\&, RectangleF) 메서드

지정된 사각형을 지정된 브러시로 채웁니다.

```cpp
void System::Drawing::Graphics::FillRectangle(const SharedPtr<Brush> &brush, RectangleF rect)
```

### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 채우는 데 사용할 [Brush](../../brush/) 객체 |
| rect | [RectangleF](../../rectanglef/) | 채울 사각형의 위치와 크기를 지정하는 [RectangleF](../../rectanglef/) 객체 |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Brush](../../brush/)
* 클래스 [Graphics](../)
* 클래스 [Rectangle](../../rectangle/)
* 클래스 [RectangleF](../../rectanglef/)
* 네임스페이스 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)