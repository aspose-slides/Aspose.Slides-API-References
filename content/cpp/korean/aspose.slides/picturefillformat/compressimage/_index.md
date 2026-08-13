---
title: CompressImage()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이미지를 도형 크기와 지정된 해상도에 따라 크기를 줄여 압축합니다. 선택적으로 잘린 영역도 삭제합니다.
type: docs
weight: 443
url: /ko/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) 메서드

이미지의 크기를 도형 크기와 지정된 해상도에 따라 줄여서 압축합니다. 선택적으로 잘린 영역도 삭제합니다.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | true인 경우 메서드는 이미지의 잘린 영역을 제거하여 크기를 더 줄일 수 있습니다. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) 열거형 값으로 지정된 압축 대상 해상도입니다. |

### 반환 값

이미지가 성공적으로 압축되었는지 여부를 나타내는 **bool**. 반환 ****true****

## 비고

이 메서드는 PowerPoint의 “Picture Format → Compress Pictures” 기능과 유사하게 이미지의 크기와 해상도를 변경합니다.

이미지가 크기가 조정되었거나 잘린 경우, 그렇지 않으면 ****false****

. 

다음 예제는 목표 해상도를 설정하고 잘린 영역을 제거하여 프레젠테이션의 이미지 크기를 줄이는 **CompressImage** 메서드 사용 방법을 보여줍니다: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// 대상 해상도 150 DPI(웹 해상도)로 이미지를 압축하고 잘린 영역을 제거합니다
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) 메서드

이미지의 크기를 도형 크기와 지정된 해상도에 따라 줄여서 압축합니다. 선택적으로 잘린 영역도 삭제합니다.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | true인 경우 메서드는 이미지의 잘린 영역을 제거하여 크기를 더 줄일 수 있습니다. |
| resolution | **float** | DPI 단위의 목표 해상도입니다. 양수여야 하며 이미지가 어떻게 리사이즈될지를 정의합니다. |

### 반환 값

이미지가 성공적으로 압축되었는지 여부를 나타내는 **bool**. 반환 ****true****

## 비고

이 메서드는 PowerPoint의 “Picture Format → Compress Pictures” 기능과 유사하게 이미지의 크기와 해상도를 변경합니다.

이미지가 크기가 조정되었거나 잘린 경우, 그렇지 않으면 ****false****

. 

다음 예제는 목표 해상도를 설정하고 잘린 영역을 제거하여 프레젠테이션의 이미지 크기를 줄이는 **CompressImage** 메서드 사용 방법을 보여줍니다: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame을 가져옵니다
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// 대상 해상도 150 DPI(웹 해상도)로 이미지를 압축하고 잘린 영역을 제거합니다
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // 웹 해상도
```

## 참조

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* 클래스 [PictureFillFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)