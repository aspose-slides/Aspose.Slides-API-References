---
title: Point()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새로운 Point 객체를 생성하고 X 및 Y 좌표 값을 0으로 초기화합니다.
type: docs
weight: 1
url: /ko/system.drawing/point/point/
---
## Point::Point() 생성자

새로운 [Point](../) 객체를 생성하고 X 및 Y 좌표 값을 0으로 초기화합니다.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) 생성자

새로운 [Point](../) 객체를 생성하고 지정된 값으로 초기화합니다.

```cpp
System::Drawing::Point::Point(int x, int y)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | X 좌표의 값 |
| y | int | Y 좌표의 값 |

## Point::Point(const Size\&) 생성자

새로운 [Point](../) 객체를 생성하고 X 및 Y 좌표 값을 해당 [SizeF](../../sizef/) 객체의 너비와 높이 값으로 각각 초기화합니다.

```cpp
System::Drawing::Point::Point(const Size &size)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size | const [Size](../../size/)\& | 생성되는 [Point](../) 객체의 X 및 Y 좌표 값을 초기화하는 데 사용되는 너비와 높이 값을 가진 [SizeF](../../sizef/) 객체 |

## Point::Point(int) 생성자

새로운 [Point](../) 객체를 생성하고 지정된 32비트 정수의 상위 16비트로 형성된 값으로 X 좌표 값을, 하위 16비트로 형성된 값으로 Y 좌표 값을 초기화합니다.

```cpp
System::Drawing::Point::Point(int dw)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dw | int | 생성되는 객체의 X 좌표 값을 지정하는 상위 16비트와 Y 좌표 값을 지정하는 하위 16비트를 포함하는 32비트 정수 값 |

## 참고

* 클래스 [Point](../)
* 클래스 [Size](../../size/)
* 네임스페이스 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)