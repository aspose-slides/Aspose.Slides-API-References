---
title: Rectangle()
second_title: Aspose.Slides for C++ API 참조
description: X 및 Y 좌표와 너비 및 높이 값을 0으로 설정한 사각형을 나타내는 Rectangle 객체의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() 생성자

[Rectangle](../) 객체의 새 인스턴스를 생성합니다. 이 객체는 X와 Y 좌표 및 너비와 높이 값을 0으로 설정한 사각형을 나타냅니다.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) 생성자

[Rectangle](../) 객체의 새 인스턴스를 생성합니다. 이 객체는 왼쪽 위 모서리의 지정된 좌표와 너비 및 높이를 가진 사각형을 나타냅니다.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| x | int | 사각형의 왼쪽 위 모서리 X 좌표 값 |
| y | int | 사각형의 왼쪽 위 모서리 Y 좌표 값 |
| width | int | 사각형의 너비 |
| height | int | 사각형의 높이 |

## Rectangle::Rectangle(const Point\&, const Size\&) 생성자

[Rectangle](../) 객체의 새 인스턴스를 생성합니다. 이 객체는 왼쪽 위 모서리 좌표를 [Point](../../point/) 클래스의 인스턴스로, 너비와 높이를 [Size](../../size/) 클래스의 인스턴스로 지정한 사각형을 나타냅니다.

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| location | const [Point](../../point/)\& | 사각형의 왼쪽 위 모서리 위치를 지정합니다 |
| size | const [Size](../../size/)\& | 사각형의 너비와 높이를 지정합니다 |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle\&) 생성자

[Rectangle](../) 객체의 새 인스턴스를 생성합니다. 이 객체는 지정된 사각형과 동일한 사각형을 나타냅니다.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | 구성되는 객체가 나타낼 사각형의 위치와 크기를 지정하는 **System::Windows::Forms::Screen::Rectangle_** 클래스의 인스턴스 |

## 참고

* 클래스 [Rectangle](../)
* 클래스 [Point](../../point/)
* 클래스 [Size](../../size/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)