---
title: RectangleF()
second_title: Aspose.Slides for C++ API 레퍼런스
description: X 및 Y 좌표와 너비 및 높이 값을 0으로 설정한 사각형을 나타내는 RectangleF 객체의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() 생성자

새로운 [RectangleF](../) 객체 인스턴스를 생성하며, 이 객체는 X 및 Y 좌표와 너비와 높이 값이 0으로 설정된 사각형을 나타냅니다.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) 생성자

새로운 [RectangleF](../) 객체 인스턴스를 생성하며, 이 객체는 왼쪽 위 모서리의 지정된 좌표와 너비 및 높이를 가진 사각형을 나타냅니다.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 사각형의 왼쪽 위 모서리 X 좌표값 |
| y | **float** | 사각형의 왼쪽 위 모서리 Y 좌표값 |
| width | **float** | 사각형의 너비 |
| height | **float** | 사각형의 높이 |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) 생성자

새로운 [RectangleF](../) 객체 인스턴스를 생성하며, 이 객체는 왼쪽 위 모서리 좌표를 [PointF](../../pointf/) 클래스의 인스턴스로 지정하고, 너비와 높이를 [SizeF](../../sizef/) 클래스의 인스턴스로 지정한 사각형을 나타냅니다.

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | 사각형의 왼쪽 위 모서리 위치를 지정합니다. |
| size | const [SizeF](../../sizef/)\& | 사각형의 너비와 높이를 지정합니다. |

## RectangleF::RectangleF(const Rectangle\&) 생성자

새로운 [RectangleF](../) 객체 인스턴스를 생성하며, 이 객체는 지정된 사각형과 동일한 사각형을 나타냅니다.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 구성되는 객체가 나타낼 사각형의 위치와 크기를 지정하는 [Rectangle](../../rectangle/) 클래스의 인스턴스 |

## 참고

* 클래스 [RectangleF](../)
* 클래스 [PointF](../../pointf/)
* 클래스 [SizeF](../../sizef/)
* 클래스 [Rectangle](../../rectangle/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)