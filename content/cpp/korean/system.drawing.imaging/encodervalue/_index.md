---
title: EncoderValue
second_title: Aspose.Slides for C++ API 참조
description: JPEG 또는 TIFF 이미지 인코더에 전달되는 매개변수 값을 지정합니다.
type: docs
weight: 261
url: /ko/system.drawing.imaging/encodervalue/
---
## EncoderValue 열거형

Specifies the parameter value passed to a JPEG or TIFF image encoder.

```cpp
enum class EncoderValue
```

### 값

| Name | Value | Description |
| --- | --- | --- |
| ColorTypeCMYK | 0 | CMYK 색 공간. |
| ColorTypeYCCK | 1 | YCCK 색 공간. |
| CompressionLZW | 2 | LZW 압축 방법. |
| CompressionCCITT3 | 3 | TIFF 이미지에 대한 CCITT3 압축 방법을 지정합니다. |
| CompressionCCITT4 | 4 | TIFF 이미지에 대한 CCITT4 압축 방법을 지정합니다. |
| CompressionRle | 5 | TIFF 이미지에 대한 RLE 압축 방법을 지정합니다. |
| CompressionNone | 6 | TIFF 이미지에 압축을 적용하지 않음을 지정합니다. |
| ScanMethodInterlaced | 7 | 인터레이스 모드. |
| ScanMethodNonInterlaced | 8 | 비인터레이스 모드. |
| VersionGif87 | 9 | TIFF 이미지에 대해 버전 87을 지정합니다. |
| VersionGif89 | 10 | GIF 이미지에 대해 버전 89a를 지정합니다. |
| RenderProgressive | 11 | 프로그레시브 모드. |
| RenderNonProgressive | 12 | 비프로그레시브 모드. |
| TransformRotate90 | 13 | JPEG 이미지에 대해 무손실 90도 시계방향 회전을 지정합니다. |
| TransformRotate180 | 14 | JPEG 이미지에 대해 무손실 180도 회전을 지정합니다. |
| TransformRotate270 | 15 | JPEG 이미지에 대해 무손실 270도 시계방향 회전을 지정합니다. |
| TransformFlipHorizontal | 16 | JPEG 이미지에 대해 무손실 수평 플립을 지정합니다. |
| TransformFlipVertical | 17 | JPEG 이미지에 대해 무손실 수직 플립을 지정합니다. |
| MultiFrame | 18 | 다중 프레임 인코딩. |
| LastFrame | 19 | 다중 프레임 이미지의 마지막 프레임. |
| Flush | 20 | 인코더 객체가 닫힙니다. |
| FrameDimensionTime | 21 | GIF 이미지에 대한 시간 프레임 차원을 지정합니다. |
| FrameDimensionResolution | 22 | 해상도 프레임 차원. |
| FrameDimensionPage | 23 | TIFF 이미지에 대한 페이지 프레임 차원을 지정합니다. |

## 참고

* 네임스페이스 [System::Drawing::Imaging](../)
* 라이브러리 [Aspose.Slides](../../)