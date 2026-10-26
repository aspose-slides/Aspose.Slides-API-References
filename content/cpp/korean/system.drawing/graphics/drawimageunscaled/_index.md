---
title: DrawImageUnscaled()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다.
type: docs
weight: 443
url: /ko/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) method


지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| x | int | 그려진 이미지의 왼쪽 위 모서리의 X 좌표 |
| y | int | 그려진 이미지의 왼쪽 위 모서리의 Y 좌표 |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) method


지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| x | int | 그려진 이미지의 왼쪽 위 모서리의 X 좌표 |
| y | int | 그려진 이미지의 왼쪽 위 모서리의 Y 좌표 |
| width | int | 사용되지 않음 |
| height | int | 사용되지 않음 |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) method


지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| rect | const [Rectangle](../../rectangle/)\& | 그려진 이미지의 왼쪽 위 모서리를 지정하는 사각형입니다. 사각형의 X 및 Y 속성이 왼쪽 위 모서리를 지정합니다. 너비와 높이 값은 무시됩니다. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) method


지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| point | const [Point](../../point/)\& | 그려진 이미지의 왼쪽 위 모서리를 지정하는 [Point](../../point/) 구조체. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Image](../../image/)
* 클래스 [Graphics](../)
* 클래스 [Rectangle](../../rectangle/)
* 클래스 [Point](../../point/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)