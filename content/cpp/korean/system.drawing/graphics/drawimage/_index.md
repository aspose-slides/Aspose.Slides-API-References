---
title: DrawImage()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 구현되지 않음.
type: docs
weight: 430
url: /ko/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) 메서드

구현되지 않음.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 무시됨 |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 무시됨 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) 메서드

지정된 위치에 지정된 이미지의 지정된 영역을 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | 이미지가 그려질 그리기 표면에 평행사변형을 정의하는 세 점을 포함하는 배열 |
| srcRect | const [RectangleF](../../rectanglef/)\& | 그릴 이미지의 영역을 정의하는 사각형 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 매개변수에 사용되는 측정 단위 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 이미지의 색상 및 감마 정보를 지정 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) 메서드

지정된 위치에 지정된 이미지의 지정된 영역을 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | 이미지가 그려질 그리기 표면에 평행사변형을 정의하는 세 점을 포함하는 배열 보기 |
| srcRect | const [RectangleF](../../rectanglef/)\& | 그릴 이미지의 영역을 정의하는 사각형 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 매개변수에 사용되는 측정 단위 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 이미지의 색상 및 감마 정보를 지정 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) 메서드

지정된 위치에 지정된 이미지의 지정된 영역을 그립니다.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | 이미지가 그려질 그리기 표면에 평행사변형을 정의하는 세 점을 포함하는 스택 배열 |
| srcRect | const [RectangleF](../../rectanglef/)\& | 그릴 이미지의 영역을 정의하는 사각형 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 매개변수에 사용되는 측정 단위 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 이미지의 색상 및 감마 정보를 지정 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) 메서드

지정된 위치에 지정된 이미지를 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| x | int | 그림이 그려질 이미지의 왼쪽 위 모서리의 X 좌표 |
| y | int | 그림이 그려질 이미지의 왼쪽 위 모서리의 Y 좌표 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) 메서드

지정된 위치에 지정된 이미지를 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| x | **float** | 그림이 그려질 이미지의 왼쪽 위 모서리의 X 좌표 |
| y | **float** | 그림이 그려질 이미지의 왼쪽 위 모서리의 Y 좌표 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) 메서드

지정된 위치에 지정된 이미지를 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| pt | [Point](../../point/) | 그림이 그려질 이미지의 왼쪽 위 모서리 위치 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) 메서드

지정된 위치에 지정된 이미지를 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| pt | [PointF](../../pointf/) | 그림이 그려질 이미지의 왼쪽 위 모서리 위치 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) 메서드

지정된 사각형에 지정된 이미지를 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| x | int | 이미지를 그릴 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | int | 이미지를 그릴 사각형의 왼쪽 위 모서리의 Y 좌표 |
| width | int | 이미지를 그릴 사각형의 너비 |
| height | int | 이미지를 그릴 사각형의 높이 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) 메서드

지정된 사각형에 지정된 이미지를 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| x | **float** | 이미지를 그릴 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | **float** | 이미지를 그릴 사각형의 왼쪽 위 모서리의 Y 좌표 |
| width | **float** | 이미지를 그릴 사각형의 너비 |
| height | **float** | 이미지를 그릴 사각형의 높이 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) 메서드

지정된 위치에 지정된 이미지의 지정된 영역을 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| destRect | [RectangleF](../../rectanglef/) | 이미지를 그릴 사각형 |
| srcRect | [RectangleF](../../rectanglef/) | 지정된 이미지의 영역을 정의하는 사각형 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 매개변수에 사용되는 측정 단위 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) 메서드

지정된 위치에 지정된 이미지의 지정된 영역을 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| destRect | [Rectangle](../../rectangle/) | 이미지를 그릴 사각형 |
| srcRect | [Rectangle](../../rectangle/) | 지정된 이미지의 영역을 정의하는 사각형 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 매개변수에 사용되는 측정 단위 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) 메서드

지정된 위치에 지정된 이미지의 지정된 영역을 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| x | int | 이미지를 그릴 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | int | 이미지를 그릴 사각형의 왼쪽 위 모서리의 Y 좌표 |
| srcRect | [Rectangle](../../rectangle/) | 지정된 이미지의 영역을 정의하는 사각형 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 매개변수에 사용되는 측정 단위 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) 메서드

지정된 위치에 지정된 이미지를 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| rect | const [Rectangle](../../rectangle/)\& | 이미지를 그릴 사각형 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) 메서드

지정된 위치에 지정된 이미지를 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| rect | const [RectangleF](../../rectanglef/)\& | 이미지를 그릴 사각형 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) 메서드

지정된 사각형에 지정된 이미지의 지정된 영역을 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| destRect | [Rectangle](../../rectangle/) | 이미지를 그릴 사각형 |
| srcX | int | 그릴 이미지의 일부분을 지정하는 사각형 왼쪽 위 모서리의 X 좌표 |
| srcY | int | 그릴 이미지의 일부분을 지정하는 사각형 왼쪽 위 모서리의 Y 좌표 |
| srcWidth | int | 그릴 이미지의 일부분을 지정하는 사각형의 너비 |
| srcHeight | int | 그릴 이미지의 일부분을 지정하는 사각형의 높이 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcX**, **srcY**, **srcWidth**, **srcHeight** 매개변수가 지정되는 측정 단위 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 이미지의 색상 및 감마 정보를 지정 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) 메서드

지정된 사각형에 지정된 이미지의 지정된 영역을 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| destRect | [Rectangle](../../rectangle/) | 이미지를 그릴 사각형 |
| srcX | **float** | 그릴 이미지의 일부분을 지정하는 사각형 왼쪽 위 모서리의 X 좌표 |
| srcY | **float** | 그릴 이미지의 일부분을 지정하는 사각형 왼쪽 위 모서리의 Y 좌표 |
| srcWidth | **float** | 그릴 이미지의 일부분을 지정하는 사각형의 너비 |
| srcHeight | **float** | 그릴 이미지의 일부분을 지정하는 사각형의 높이 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcX**, **srcY**, **srcWidth**, **srcHeight** 매개변수가 지정되는 측정 단위 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 이미지의 색상 및 감마 정보를 지정 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) 메서드

지정된 사각형에 지정된 이미지의 지정된 영역을 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| destRect | [Rectangle](../../rectangle/) | 이미지를 그릴 사각형 |
| srcX | int | 그릴 이미지의 일부분을 지정하는 사각형 왼쪽 위 모서리의 X 좌표 |
| srcY | int | 그릴 이미지의 일부분을 지정하는 사각형 왼쪽 위 모서리의 Y 좌표 |
| srcWidth | int | 그릴 이미지의 일부분을 지정하는 사각형의 너비 |
| srcHeight | int | 그릴 이미지의 일부분을 지정하는 사각형의 높이 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcX**, **srcY**, **srcWidth**, **srcHeight** 매개변수가 지정되는 측정 단위 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) 메서드

지정된 사각형에 지정된 이미지의 지정된 영역을 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| destRect | [Rectangle](../../rectangle/) | 이미지를 그릴 사각형 |
| srcX | **float** | 그릴 이미지의 일부분을 지정하는 사각형 왼쪽 위 모서리의 X 좌표 |
| srcY | **float** | 그릴 이미지의 일부분을 지정하는 사각형 왼쪽 위 모서리의 Y 좌표 |
| srcWidth | **float** | 그릴 이미지의 일부분을 지정하는 사각형의 너비 |
| srcHeight | **float** | 그릴 이미지의 일부분을 지정하는 사각형의 높이 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcX**, **srcY**, **srcWidth**, **srcHeight** 매개변수가 지정되는 측정 단위 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) 메서드

구현되지 않음.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) 메서드

구현되지 않음.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) 메서드

구현되지 않음.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) 메서드

구현되지 않음.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) 메서드

구현되지 않음.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) 메서드

구현되지 않음.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) 메서드

구현되지 않음.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) 메서드

지정된 위치에 지정된 이미지의 지정된 영역을 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 이미지가 그려질 그리기 표면에 평행사변형을 정의하는 세 점을 포함하는 배열 |
| srcRect | [Rectangle](../../rectangle/) | 지정된 이미지의 영역을 정의하는 사각형 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 매개변수에 사용되는 측정 단위 |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | 이미지의 색상 및 감마 정보를 지정 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) 메서드

지정된 위치에 지정된 이미지의 지정된 영역을 그립니다.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 그릴 이미지 |
| x | **float** | 이미지를 그릴 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | **float** | 이미지를 그릴 사각형의 왼쪽 위 모서리의 Y 좌표 |
| srcRect | [RectangleF](../../rectanglef/) | 지정된 이미지의 영역을 정의하는 사각형 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 매개변수에 사용되는 측정 단위 |

## 참고

* 열거형 [GraphicsUnit](../../graphicsunit/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* 타입정의 [DrawImageAbort](../drawimageabort/)
* 클래스 [Image](../../image/)
* 클래스 [Point](../../point/)
* 클래스 [Graphics](../)
* 클래스 [PointF](../../pointf/)
* 클래스 [RectangleF](../../rectanglef/)
* 클래스 [Rectangle](../../rectangle/)
* 클래스 [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)