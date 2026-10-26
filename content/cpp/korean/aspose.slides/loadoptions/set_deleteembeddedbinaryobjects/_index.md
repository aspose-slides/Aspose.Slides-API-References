---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides C++ API 레퍼런스
description: 프레젠테이션을 로드하는 동안 Aspose.Slides가 모든 임베디드 바이너리 개체를 삭제할지 여부를 결정합니다.
type: docs
weight: 352
url: /ko/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) method


프레젠테이션 로드 중에 [Aspose.Slides](../../)가 모든 임베디드 바이너리 개체를 삭제할지 여부를 결정합니다.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## 비고


임베디드 바이너리 개체의 유형:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


작성 **bool**. 

기본값은 **false**. 

다음 예제는 임베디드 바이너리 개체 없이 프레젠테이션을 로드하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## 참고

* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)