---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션 로드 중에 Aspose.Slides가 모든 포함된 이진 객체를 삭제할지 여부를 결정합니다.
type: docs
weight: 339
url: /ko/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() 메서드

프레젠테이션 로드 중에 [Aspose.Slides](../../)가 모든 포함된 이진 객체를 삭제할지 여부를 결정합니다.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## 비고

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

읽기 **bool**.

기본값은 **false**.

다음 예제는 포함된 이진 객체 없이 프레젠테이션을 로드하는 방법을 보여줍니다.
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## 참고

* 클래스 [ILoadOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)