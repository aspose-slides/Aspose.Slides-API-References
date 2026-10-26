---
title: SetClip()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 Graphics 객체가 나타내는 그리기 표면의 클리핑 영역을 현재 클립 영역과 지정된 영역을 결합하는 지정된 연산의 결과로 설정합니다.
type: docs
weight: 690
url: /ko/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) 메서드

현재 [Graphics](../) 객체가 나타내는 그리기 표면의 클리핑 영역을 현재 클립 영역과 지정된 영역을 결합하는 지정된 연산의 결과로 설정합니다.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | 결합할 영역을 지정합니다 |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 결합 연산을 지정합니다 |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) 메서드

현재 [Graphics](../) 객체가 나타내는 그리기 표면의 클리핑 영역을 현재 클립 영역과 지정된 영역을 결합하는 지정된 연산의 결과로 설정합니다.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | 결합할 영역을 지정합니다 |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 결합 연산을 지정합니다 |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) 메서드

현재 [Graphics](../) 객체가 나타내는 그리기 표면의 클리핑 영역을 현재 클립 영역과 지정된 영역을 결합하는 지정된 연산의 결과로 설정합니다.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | 결합할 영역을 지정합니다 |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 결합 연산을 지정합니다 |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) 메서드

구현되지 않음.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) 메서드

현재 [Graphics](../) 객체가 나타내는 그리기 표면의 클리핑 영역을 현재 클립 영역과 그래픽스 경로로 지정된 영역을 결합하는 지정된 연산의 결과로 설정합니다.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 결합할 영역을 지정합니다 |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 결합 연산을 지정합니다 |

## 참고

* 열거형 [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Region](../../region/)
* 클래스 [Graphics](../)
* 클래스 [Rectangle](../../rectangle/)
* 클래스 [RectangleF](../../rectanglef/)
* 클래스 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)