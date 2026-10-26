---
title: ImageFlags
second_title: Aspose.Slides for C++ API 레퍼런스
description: Image 객체가 나타내는 픽셀 데이터의 속성을 나타냅니다.
type: docs
weight: 274
url: /ko/system.drawing.imaging/imageflags/
---
## ImageFlags 열거형

[Image](../../system.drawing/image/) 객체가 나타내는 픽셀 데이터의 속성을 나타냅니다.

```cpp
enum class ImageFlags
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | 확장 가능. |
| HasAlpha | 2 | 알파 정보를 포함합니다. |
| HasTranslucent | 4 | 알파 값이 0보다 크고 255보다 작은 경우가 있습니다. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | 픽셀 데이터가 RGB 색 공간으로 표시됩니다. |
| ColorSpaceCmyk | 32 | 픽셀 데이터가 CMYK 색 공간으로 표시됩니다. |
| ColorSpaceGray | 64 | 픽셀 데이터가 그레이스케일입니다. |
| ColorSpaceYcbcr | 128 | 픽셀 데이터가 YCBCR 색 공간으로 표시됩니다. |
| ColorSpaceYcck | 256 | 픽셀 데이터가 YCCK 색 공간으로 표시됩니다. |
| HasRealDpi | 4096 | 이미지에 DPI 정보가 저장됩니다. |
| HasRealPixelSize | 8192 | 이미지에 픽셀 크기가 저장됩니다. |
| ReadOnly | 65536 | 픽셀 데이터는 읽기 전용입니다. |
| Caching | 131072 | 더 빠른 접근을 위해 캐시할 수 있습니다. |

## 참조

* 네임스페이스 [System::Drawing::Imaging](../)
* 라이브러리 [Aspose.Slides](../../)