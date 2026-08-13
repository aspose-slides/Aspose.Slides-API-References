---
title: IntersectClip()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 개체의 클립 영역을 현재 클립과 지정된 클립의 교차 영역으로 업데이트합니다.
type: docs
weight: 950
url: /ko/system.drawing/graphics/intersectclip/
---
## Graphics::IntersectClip(const System::SharedPtr\<Region\>\&) 메서드

이 개체의 클립 영역을 현재 클립과 지정된 클립의 교차 영역으로 업데이트합니다.

```cpp
void System::Drawing::Graphics::IntersectClip(const System::SharedPtr<Region> &region)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | const [System::SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | 교차할 영역 |

## Graphics::IntersectClip(System::Drawing::RectangleF) 메서드

이 개체의 클립 영역을 현재 클립과 지정된 클립의 교차 영역으로 업데이트합니다.

```cpp
void System::Drawing::Graphics::IntersectClip(System::Drawing::RectangleF rect)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [System::Drawing::RectangleF](../../rectanglef/) | 교차할 사각형 |

## Graphics::IntersectClip(System::Drawing::Rectangle) 메서드

이 개체의 클립 영역을 현재 클립과 지정된 클립의 교차 영역으로 업데이트합니다.

```cpp
void System::Drawing::Graphics::IntersectClip(System::Drawing::Rectangle rect)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [System::Drawing::Rectangle](../../rectangle/) | 교차할 사각형 |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Region](../../region/)
* 클래스 [Graphics](../)
* 클래스 [RectangleF](../../rectanglef/)
* 클래스 [Rectangle](../../rectangle/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)