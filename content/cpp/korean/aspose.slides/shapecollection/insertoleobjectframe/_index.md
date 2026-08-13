---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 OLE 개체 프레임을 생성하고 지정된 인덱스에 ShapeCollection에 삽입합니다.
type: docs
weight: 196
url: /ko/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) 메서드


새 OLE 개체 프레임을 생성하고 지정된 인덱스에 ShapeCollection에 삽입합니다.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | OLE 개체 프레임을 삽입할 0 기반 인덱스. |
| x | **float** | 새 OLE 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 OLE 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 OLE 프레임의 너비(포인트 단위). |
| height | **float** | 새 OLE 프레임의 높이(포인트 단위). |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 내장 OLE 데이터 정보 ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### 반환값

새로 생성된 [IOleObjectFrame](../../ioleobjectframe/).

## 비고



이 예제는 두 번째 인덱스에 OLE 개체를 삽입하는 방법을 보여줍니다:
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) 메서드


새 OLE 개체 프레임을 생성하고 지정된 인덱스에 ShapeCollection에 삽입합니다.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | OLE 개체 프레임을 삽입할 0 기반 인덱스. |
| x | **float** | 새 OLE 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 OLE 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 OLE 프레임의 너비(포인트 단위). |
| height | **float** | 새 OLE 프레임의 높이(포인트 단위). |
| className | [System::String](../../../system/string/) | OLE 개체의 클래스 이름. |
| path | [System::String](../../../system/string/) | 링크된 파일의 경로. |

### 반환값

새로 생성된 OLE 개체 프레임.

## 비고



이 경로는 프레젠테이션에 있는 그대로 저장됩니다. 상대 경로를 지정하면 다른 디렉터리에서 프레젠테이션을 열 때 파일에 접근할 수 없습니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IOleObjectFrame](../../ioleobjectframe/)
* 클래스 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 클래스 [ShapeCollection](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)