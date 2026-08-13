---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 OLE 객체 프레임을 생성하고 이를 도형 컬렉션의 끝에 추가합니다.
type: docs
weight: 183
url: /ko/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) 메서드


새 OLE 객체 프레임을 생성하고 이를 도형 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 새 OLE 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 OLE 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 OLE 프레임의 너비(포인트 단위). |
| height | **float** | 새 OLE 프레임의 높이(포인트 단위). |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 임베드된 OLE 데이터에 대한 정보([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### 반환값

새로 생성된 [IOleObjectFrame](../../ioleobjectframe/).
## 비고



다음 예제는 PowerPoint [Presentation](../../presentation/)의 [Slides](../../)에 OLE 객체 프레임을 추가하는 방법을 보여줍니다.
```cpp
auto pres = System::MakeObject<Presentation>();

// 첫 번째 슬라이드에 접근합니다
auto slide = pres->get_Slides()->idx_get(0);
// 엑셀 파일을 스트림으로 로드합니다
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// 임베딩용 데이터 객체를 생성합니다
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Ole Object Frame 도형을 추가합니다
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
//PPTX 파일을 디스크에 저장합니다
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) 메서드


새 OLE 객체 프레임을 생성하고 이를 도형 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 새 OLE 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 OLE 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 OLE 프레임의 너비(포인트 단위). |
| height | **float** | 새 OLE 프레임의 높이(포인트 단위). |
| className | [System::String](../../../system/string/) | OLE 객체의 클래스 이름. |
| path | [System::String](../../../system/string/) | 링크된 파일의 경로. |

### 반환값

새로 생성된 [IOleObjectFrame](../../ioleobjectframe/).
## 비고



이 경로는 프레젠테이션에 그대로 저장됩니다. 상대 경로를 지정하면 다른 디렉터리에서 프레젠테이션을 열 때 파일에 접근할 수 없습니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IOleObjectFrame](../../ioleobjectframe/)
* 클래스 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 클래스 [ShapeCollection](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)