---
title: ReplaceImage()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이미지 데이터를 교체합니다.
type: docs
weight: 118
url: /ko/aspose.slides/ppimage/replaceimage/
---
## PPImage::ReplaceImage(System::ArrayPtr\<uint8_t\>) 메서드

이미지 데이터를 교체합니다.

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::ArrayPtr<uint8_t> newImageData) override
```
## PPImage::ReplaceImage(System::SharedPtr\<Aspose::Slides::IImage\>) 메서드

이미지 데이터를 교체합니다. 주의: Image가 메타파일인 경우 래스터화됩니다. 대신 ReplaceImage(byte[])를 사용하십시오.

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::SharedPtr<Aspose::Slides::IImage> newImage) override
```

## PPImage::ReplaceImage(System::SharedPtr\<Aspose::Slides::IPPImage\>) 메서드

이미지 데이터를 교체합니다.

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::SharedPtr<Aspose::Slides::IPPImage> newImage) override
```
## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [PPImage](../)
* 클래스 [IImage](../../iimage/)
* 클래스 [IPPImage](../../ippimage/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)