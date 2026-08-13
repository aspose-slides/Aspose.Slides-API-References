---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션을 로드하는 동안 Aspose.Slides가 모든 임베디드 바이너리 객체를 삭제할지 여부를 결정합니다.
type: docs
weight: 339
url: /ko/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() 메서드


[Aspose.Slides](../../)가 프레젠테이션 로드 중 모든 임베디드 바이너리 객체를 삭제할지 여부를 결정합니다.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## 비고


임베디드 바이너리 객체의 유형:

* VBA 프로젝트 [IPresentation::VbaProject](../)
* OLE 객체 임베디드 데이터 [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) 바이너리 데이터 [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


읽기 **bool**. 
기본값은 **false**. 
다음 예제는 임베디드 바이너리 객체 없이 프레젠테이션을 로드하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## 관련 항목

* 클래스 [LoadOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)