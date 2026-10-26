---
title: Inflate()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 양만큼 양쪽 방향으로 증가합니다.
type: docs
weight: 261
url: /ko/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) 메서드

현재 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 양만큼 양쪽 방향으로 증가합니다.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| width | **float** | 사각형의 너비를 양쪽 방향으로 증가시킬 양 |
| height | **float** | 사각형의 높이를 양쪽 방향으로 증가시킬 양 |

## RectangleF::Inflate(const SizeF\&) 메서드

현재 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 size 객체의 width 및 height 값에 해당하는 양만큼 각각 증가합니다.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | 사각형의 너비와 높이를 증가시킬 양을 지정하는 [SizeF](../../sizef/) 객체 |

## RectangleF::Inflate(const RectangleF\&, float, float) 메서드

지정된 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 양만큼 양쪽 방향으로 증가합니다.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | 확장할 사각형 |
| x | **float** | 사각형의 너비를 양쪽 방향으로 증가시킬 양 |
| y | **float** | 사각형의 높이를 양쪽 방향으로 증가시킬 양 |

### 반환값

확대된 사각형을 나타내는 [RectangleF](../) 객체

## 참고

* 클래스 [RectangleF](../)
* 클래스 [SizeF](../../sizef/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)