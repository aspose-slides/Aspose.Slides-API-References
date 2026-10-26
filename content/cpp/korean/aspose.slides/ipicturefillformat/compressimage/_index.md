---
title: CompressImage()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 도형 크기와 지정된 해상도를 기반으로 이미지 크기를 줄여 압축합니다. 선택적으로 잘린 영역을 삭제할 수도 있습니다.
type: docs
weight: 443
url: /ko/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) 메서드

이 메서드는 도형 크기와 지정된 해상도를 기반으로 이미지의 크기를 줄여 압축합니다. 선택적으로 잘린 영역을 삭제할 수도 있습니다.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | true인 경우, 이 메서드는 이미지의 잘린 영역을 제거하여 크기를 더 줄일 수 있습니다. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | 압축을 위한 목표 해상도이며, [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) 열거형 값으로 지정됩니다. |

### 반환값

이미지가 성공적으로 압축되었는지 여부를 나타내는 **bool**입니다. ****true****를 반환합니다.

## 비고

이 메서드는 PowerPoint의 "Picture Format -> Compress Pictures" 기능과 유사하게 이미지의 크기와 해상도를 변경합니다.

이미지가 크기가 조정되거나 잘린 경우, 그렇지 않으면 ****false****.

.

다음 예제는 목표 해상도를 설정하고 잘린 영역을 제거하여 프레젠테이션 내 이미지의 크기를 줄이는 **CompressImage** 메서드 사용법을 보여 줍니다: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// 대상 해상도 150 DPI(웹 해상도)로 이미지를 압축하고 잘린 영역을 제거합니다.
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) 메서드

이 메서드는 도형 크기와 지정된 해상도를 기반으로 이미지의 크기를 줄여 압축합니다. 선택적으로 잘린 영역을 삭제할 수도 있습니다.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | true인 경우, 이 메서드는 이미지의 잘린 영역을 제거하여 크기를 더 줄일 수 있습니다. |
| resolution | **float** | 목표 해상도(DPI)입니다. 이 값은 양수이어야 하며 이미지가 어떻게 크기 조정될지를 정의합니다. |

### 반환값

이미지가 성공적으로 압축되었는지 여부를 나타내는 **bool**입니다. ****true****를 반환합니다.

## 비고

이 메서드는 PowerPoint의 "Picture Format -> Compress Pictures" 기능과 유사하게 이미지의 크기와 해상도를 변경합니다.

이미지가 크기가 조정되거나 잘린 경우, 그렇지 않으면 ****false****.

.

다음 예제는 목표 해상도를 설정하고 잘린 영역을 제거하여 프레젠테이션 내 이미지의 크기를 줄이는 **CompressImage** 메서드 사용법을 보여 줍니다: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame을 가져옵니다
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// 대상 해상도 150 DPI(웹 해상도)로 이미지를 압축하고 잘린 영역을 제거합니다
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // 웹 해상도
```

## 관련 항목

* 열거형 [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* 클래스 [IPictureFillFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)