---
title: LockBits()
second_title: Aspose.Slides용 C++ API 레퍼런스
description: Bitmap을 시스템 메모리로 잠급니다.
type: docs
weight: 118
url: /ko/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) 메서드


시스템 메모리로 [Bitmap](../)를 잠급니다.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 잠그려는 이미지 영역을 지정하는 사각형 |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | 비트맵에 대한 액세스 수준을 지정합니다 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 이 비트맵의 데이터 형식 |

### 반환값

수행된 잠금 작업에 대한 정보를 포함하는 BitmapData 객체에 대한 공유 포인터

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) 메서드


시스템 메모리로 [Bitmap](../)를 잠급니다.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 잠그려는 이미지 영역을 지정하는 사각형 |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | 비트맵에 대한 액세스 수준을 지정합니다 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 이 비트맵의 데이터 형식 |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | 잠금 작업에 대한 정보를 포함합니다 |

### 반환값

수행된 잠금 작업에 대한 정보를 포함하는 BitmapData 객체에 대한 공유 포인터

## 참고

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)