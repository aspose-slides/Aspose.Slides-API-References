---
title: get_Images()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션에 포함된 모든 이미지의 컬렉션을 반환합니다. 읽기 전용 IImageCollection.
type: docs
weight: 209
url: /ko/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() 메서드

프레젠테이션에 포함된 모든 이미지의 컬렉션을 반환합니다. 읽기 전용 [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## 비고

다음 예제는 PowerPoint에 이미지를 BLOB으로 추가하는 방법을 보여줍니다 [Presentation](../). 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// 이미지를 추가할 새 프레젠테이션을 생성합니다.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// 이미지를 프레젠테이션에 추가합니다 - KeepLocked 동작을 선택하는 이유는 우리가
// "largeImage.png" 파일에 접근하려고 하지 않기 때문입니다.
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// 프레젠테이션을 저장합니다. 큰 프레젠테이션을 출력하는 동안에도
// pres 객체의 수명 동안 메모리 사용량이 낮게 유지됩니다.
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 다음 예제는 PowerPoint에서 이미지에 하이퍼링크를 추가합니다 [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// 프레젠테이션에 이미지를 추가합니다
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Creates picture frame on slide 1 based on previously added image
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImageCollection](../../iimagecollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)