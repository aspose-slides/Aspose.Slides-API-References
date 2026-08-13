---
title: Inflate()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 양만큼 양 방향으로 증가합니다.
type: docs
weight: 261
url: /ko/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) 메서드

현재 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 양만큼 양 방향으로 증가합니다.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| width | int | 사각형의 너비를 양 방향으로 증가시킬 양 |
| height | int | 사각형의 높이를 양 방향으로 증가시킬 양 |

## Rectangle::Inflate(const Size\&) 메서드

현재 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 Size 객체의 width와 height 값에 따라 각각 증가합니다.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size | const [Size](../../size/)\& | [Size](../../size/) 객체로, 사각형의 너비와 높이를 증가시킬 양을 지정합니다 |

## Rectangle::Inflate(const Rectangle\&, int, int) 메서드

지정된 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 양만큼 양 방향으로 증가합니다.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | 확장할 사각형 |
| x | int | 사각형의 너비를 양 방향으로 증가시킬 양 |
| y | int | 사각형의 높이를 양 방향으로 증가시킬 양 |

### 반환값

확장된 사각형을 나타내는 [Rectangle](../) 객체

## 참고

* 클래스 [Rectangle](../)
* 클래스 [Size](../../size/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)