---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 OLE 객체 프레임을 생성하고 형상 컬렉션 끝에 추가합니다.
type: docs
weight: 66
url: /ko/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method

새 OLE 객체 프레임을 생성하고 형상 컬렉션 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 OLE 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 OLE 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 OLE 프레임의 width(포인트 단위). |
| height | **float** | 새 OLE 프레임의 height(포인트 단위). |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 내장 OLE 데이터 정보([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### 반환 값

새로 생성된 [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method

새 OLE 객체 프레임을 생성하고 형상 컬렉션 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 OLE 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 OLE 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 OLE 프레임의 width(포인트 단위). |
| height | **float** | 새 OLE 프레임의 height(포인트 단위). |
| className | [System::String](../../../system/string/) | OLE 객체의 className. |
| path | [System::String](../../../system/string/) | 연결된 파일의 path. |

### 반환 값

새로 생성된 [IOleObjectFrame](../../ioleobjectframe/).

## 비고

이 경로는 프레젠테이션에 그대로 저장됩니다. 상대 경로가 지정되면 다른 디렉터리에서 프레젠테이션을 열 때 파일에 접근할 수 없습니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)