---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 OLE 개체 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다.
type: docs
weight: 79
url: /ko/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) 메서드

새 OLE 개체 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | OLE 개체 프레임을 삽입할 0 기반 인덱스입니다. |
| x | **float** | 새 OLE 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 OLE 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 OLE 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새 OLE 프레임의 높이(포인트 단위)입니다. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 내장 OLE 데이터 정보([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/))입니다. |

### 반환 값

새로 만든 [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) 메서드

새 OLE 개체 프레임을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | OLE 개체 프레임을 삽입할 0 기반 인덱스입니다. |
| x | **float** | 새 OLE 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 OLE 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 OLE 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새 OLE 프레임의 높이(포인트 단위)입니다. |
| className | [System::String](../../../system/string/) | OLE 개체의 클래스 이름입니다. |
| path | [System::String](../../../system/string/) | 링크된 파일의 경로입니다. |

### 반환 값

새로 만든 [IOleObjectFrame](../../ioleobjectframe/).

## 참고

이 경로는 프레젠테이션에 그대로 저장됩니다. 상대 경로를 지정하면 다른 디렉터리에서 프레젠테이션을 열 때 파일에 접근할 수 없습니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)