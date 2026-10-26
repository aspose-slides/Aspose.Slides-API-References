---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 채우기 이미지의 잘린 영역을 삭제합니다.
type: docs
weight: 430
url: /ko/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() 메서드

채우기 [Picture](../../picture/)의 잘린 영역을 삭제합니다.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```

### 반환 값

크롭이 필요하지 않은 경우 잘린 이미지 또는 원본 이미지를 반환합니다.

## 비고

이 메서드는 크롭하면서 WMF/EMF 메타파일을 래스터 PNG 이미지로 변환합니다.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame을 가져옵니다
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// PictureFrame 이미지의 잘린 영역을 삭제합니다
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPPImage](../../ippimage/)
* 클래스 [IPictureFillFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)