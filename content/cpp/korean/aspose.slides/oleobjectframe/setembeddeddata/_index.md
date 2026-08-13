---
title: SetEmbeddedData()
second_title: Aspose.Slides for C++ API 레퍼런스
description: OLE 임베디드 데이터에 대한 정보를 설정합니다.
type: docs
weight: 248
url: /ko/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) 메서드


OLE 임베디드 데이터에 대한 정보를 설정합니다.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 임베디드 데이터 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## 비고


이 메서드는 새 데이터가 반영되도록 객체의 속성을 변경하고 IsObjectLink 플래그를 false로 설정하여 OLE 객체가 임베디드됨을 나타냅니다. 

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 클래스 [OleObjectFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)