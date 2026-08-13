---
title: Contains()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 점이 현재 객체가 나타내는 사각형 내부에 있는지 확인합니다.
type: docs
weight: 248
url: /ko/system.drawing/rectangle/contains/
---
## Rectangle::Contains(int, int) const 메서드

지정된 점이 현재 객체가 나타내는 사각형 내부에 있는지 확인합니다.

```cpp
bool System::Drawing::Rectangle::Contains(int x, int y) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 검사할 점의 X 좌표 |
| y | int | 검사할 점의 Y 좌표 |

### 반환값

지정된 점이 현재 객체가 나타내는 사각형 내부에 있으면 True, 그렇지 않으면 - false

## Rectangle::Contains(const Point\&) const 메서드

지정된 점이 현재 객체가 나타내는 사각형 내부에 있는지 확인합니다.

```cpp
bool System::Drawing::Rectangle::Contains(const Point &point) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | const [Point](../../point/)\& | 검사할 점 |

### 반환값

지정된 점이 현재 객체가 나타내는 사각형 내부에 있으면 True, 그렇지 않으면 - false

## Rectangle::Contains(const Rectangle\&) const 메서드

지정된 사각형이 현재 객체가 나타내는 사각형 내부에 있는지 확인합니다.

```cpp
bool System::Drawing::Rectangle::Contains(const Rectangle &rect) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | 검사할 사각형 |

### 반환값

지정된 사각형이 현재 객체가 나타내는 사각형 내부에 있으면 True, 그렇지 않으면 - false

## 참조

* 클래스 [Rectangle](../)
* 클래스 [Point](../../point/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)