---
title: DrawRectangle()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 사각형을 그립니다.
type: docs
weight: 287
url: /ko/system.drawing/graphics/drawrectangle/
---
## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, int, int, int, int) 메서드


현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 사각형을 그립니다.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, int x, int y, int width, int height)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 사각형을 그릴 때 사용할 펜 |
| x | int | 그릴 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | int | 그릴 사각형의 왼쪽 위 모서리의 Y 좌표 |
| width | int | 그릴 사각형의 너비 |
| height | int | 그릴 사각형의 높이 |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, float, float, float, float) 메서드


현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 사각형을 그립니다.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, float x, float y, float width, float height)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 사각형을 그릴 때 사용할 펜 |
| x | **float** | 그릴 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | **float** | 그릴 사각형의 왼쪽 위 모서리의 Y 좌표 |
| width | **float** | 그릴 사각형의 너비 |
| height | **float** | 그릴 사각형의 높이 |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, Rectangle) 메서드


현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 사각형을 그립니다.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, Rectangle rect)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 사각형을 그릴 때 사용할 펜 |
| rect | [Rectangle](../../rectangle/) | [Rectangle](../../rectangle/) 객체는 그릴 사각형의 위치와 크기를 지정합니다. |

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Pen](../../pen/)
* 클래스 [Graphics](../)
* 클래스 [Rectangle](../../rectangle/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)