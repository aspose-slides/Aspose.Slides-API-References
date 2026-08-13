---
title: Clone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체의 복사본을 생성합니다.
type: docs
weight: 183
url: /ko/system.drawing/bitmap/clone/
---
## Bitmap::Clone() 메서드


현재 객체의 복사본을 생성합니다.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```


### 반환 값

현재 객체의 복사본.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) 메서드


현재 객체가 나타내는 비트맵 이미지의 영역 복사본을 나타내는 [Bitmap](../) 객체를 생성합니다.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | 복사할 영역을 지정하는 사각형 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 새 [Bitmap](../)의 픽셀 형식 |

### 반환 값

생성된 [Bitmap](../) 객체

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) 메서드


현재 객체가 나타내는 비트맵 이미지의 영역 복사본을 나타내는 [Bitmap](../) 객체를 생성합니다.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | 복사할 영역을 지정하는 사각형 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 새 [Bitmap](../)의 픽셀 형식 |

### 반환 값

생성된 [Bitmap](../) 객체

## 참고

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)