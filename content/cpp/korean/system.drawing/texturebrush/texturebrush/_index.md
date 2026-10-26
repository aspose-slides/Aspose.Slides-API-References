---
title: TextureBrush()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이미지를 사용하는 TextureBrush 클래스의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) 생성자

지정된 이미지를 사용하는 [TextureBrush](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 브러시가 도형 내부를 채우는 데 사용하는 이미지 |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | 브러시 객체가 타일링되는 방식을 지정합니다 |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) 생성자

지정된 이미지를 사용하는 [TextureBrush](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 브러시가 도형 내부를 채우는 데 사용하는 이미지 |
| dst_rect | [RectangleF](../../rectanglef/) | 브러시의 경계 사각형을 지정합니다 |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | 이미지 속성 |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) 생성자

지정된 이미지를 사용하는 [TextureBrush](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 브러시가 도형 내부를 채우는 데 사용하는 이미지 |
| dst_rect | [Rectangle](../../rectangle/) | 브러시의 경계 사각형을 지정합니다 |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | 이미지 속성 |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) 생성자

지정된 이미지를 사용하는 [TextureBrush](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 브러시가 도형 내부를 채우는 데 사용하는 이미지 |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | 브러시 객체가 타일링되는 방식을 지정합니다 |
| dst_rect | [RectangleF](../../rectanglef/) | 브러시의 경계 사각형을 지정합니다 |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) 생성자

지정된 이미지를 사용하는 [TextureBrush](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 브러시가 도형 내부를 채우는 데 사용하는 이미지 |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | 브러시 객체가 타일링되는 방식을 지정합니다 |
| dst_rect | [Rectangle](../../rectangle/) | 브러시의 경계 사각형을 지정합니다 |

## 참고

* Enum [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Image](../../image/)
* 클래스 [TextureBrush](../)
* 클래스 [RectangleF](../../rectanglef/)
* 클래스 [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* 클래스 [Rectangle](../../rectangle/)
* 네임스페이스 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)