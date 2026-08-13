---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 채우기 그림의 잘린 영역을 삭제합니다.
type: docs
weight: 430
url: /ko/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() 메서드

채우기 [Picture](../../picture/)의 잘린 영역을 삭제합니다.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```

### 반환값

잘린 이미지 또는 자르기가 필요하지 않은 경우 원본 이미지.

## 비고

이 메서드는 자르는 동안 WMF/EMF 메타파일을 래스터 PNG 이미지로 변환합니다.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame을 가져옵니다
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// PictureFrame 이미지의 잘린 영역을 삭제합니다
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../../ippimage/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)