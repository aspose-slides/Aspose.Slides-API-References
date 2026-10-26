---
title: SetEmbeddedData()
second_title: Aspose.Slides for C++ API 참조
description: OLE 임베디드 데이터에 대한 정보를 설정합니다.
type: docs
weight: 248
url: /ko/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) 메서드


OLE 임베디드 데이터에 대한 정보를 설정합니다.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 임베디드 데이터 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## 비고


이 메서드는 개체의 속성을 새 데이터에 맞게 변경하고 IsObjectLink 플래그를 false로 설정하여 OLE 개체가 임베디드됨을 나타냅니다.


다음 예제는 기존 [IOleObjectFrame](../) 개체에 대해 OLE 임베디드 데이터를 변경하고 해당 유형을 변경하는 방법을 보여줍니다.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 클래스 [IOleObjectFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)