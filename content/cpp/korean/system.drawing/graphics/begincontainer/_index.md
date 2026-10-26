---
title: BeginContainer()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 객체의 현재 상태를 저장한 컨테이너를 저장하고, 새 컨테이너를 열어 사용한 뒤 저장된 컨테이너를 반환합니다.
type: docs
weight: 976
url: /ko/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() 메서드


이 객체의 현재 상태를 저장한 컨테이너를 저장하고, 새 컨테이너를 열어 사용한 뒤 저장된 컨테이너를 반환합니다.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) 메서드


이 객체의 현재 상태를 저장한 컨테이너를 저장하고, 새 컨테이너를 열어 사용한 뒤 저장된 컨테이너를 반환합니다.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | 새 컨테이너의 스케일 변환을 지정하는 사각형입니다. **srcrect**와 함께 사용됩니다. |
| srcrect | [Rectangle](../../rectangle/) | 새 컨테이너의 스케일 변환을 지정하는 사각형입니다. **dstrect**와 함께 사용됩니다. |
| unit | [GraphicsUnit](../../graphicsunit/) | 새 컨테이너의 측정 단위를 지정하는 값입니다. |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) 메서드


이 객체의 현재 상태를 저장한 컨테이너를 저장하고, 새 컨테이너를 열어 사용한 뒤 저장된 컨테이너를 반환합니다.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | 새 컨테이너의 스케일 변환을 지정하는 사각형입니다. **srcrect**와 함께 사용됩니다. |
| srcrect | [RectangleF](../../rectanglef/) | 새 컨테이너의 스케일 변환을 지정하는 사각형입니다. **dstrect**와 함께 사용됩니다. |
| unit | [GraphicsUnit](../../graphicsunit/) | 새 컨테이너의 측정 단위를 지정하는 값입니다. |

## 참고

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)