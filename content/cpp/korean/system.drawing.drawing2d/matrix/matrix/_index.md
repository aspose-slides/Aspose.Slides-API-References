---
title: Matrix()
second_title: Aspose.Slides for C++ API 참조
description: 항등 행렬을 나타내는 Matrix 클래스의 새로운 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() 생성자

새로운 [Matrix](../) 클래스의 인스턴스를 생성하며, 이는 항등 행렬을 나타냅니다.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) 생성자

새로운 [Matrix](../) 클래스의 인스턴스를 생성하고 지정된 값으로 초기화합니다.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| m11 | **float** | 1번째 행 1번째 열의 값 |
| m12 | **float** | 1번째 행 2번째 열의 값 |
| m21 | **float** | 2번째 행 1번째 열의 값 |
| m22 | **float** | 2번째 행 2번째 열의 값 |
| dx | **float** | 3번째 행 1번째 열의 값 |
| dy | **float** | 3번째 행 2번째 열의 값 |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) 생성자

지정된 사각형과 포인트 배열에 의해 정의된 기하 변환을 위해 [Matrix](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) 생성자

지정된 사각형과 포인트 배열에 의해 정의된 기하 변환을 위해 [Matrix](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Matrix](../)
* 클래스 [Rectangle](../../../system.drawing/rectangle/)
* 클래스 [Point](../../../system.drawing/point/)
* 클래스 [RectangleF](../../../system.drawing/rectanglef/)
* 클래스 [PointF](../../../system.drawing/pointf/)
* 네임스페이스 [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)