---
title: InsertPictureFrame()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다.
type: docs
weight: 417
url: /ko/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) 메서드

지정된 이미지를 포함하는 새 그림 프레임을 생성하고 지정된 인덱스에 해당 그림 프레임을 도형 컬렉션에 삽입합니다.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 그 그림 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/)에 포함된 도형 유형을 지정하지만, 모든 종류의 선은 제외합니다:\

[ShapeType::Line](../../shapetype/),\
\
[ShapeType::StraightConnector1](../../shapetype/),\
\
[ShapeType::BentConnector2](../../shapetype/),\
\
[ShapeType::BentConnector3](../../shapetype/),\
\
[ShapeType::BentConnector4](../../shapetype/),\
\
[ShapeType::BentConnector5](../../shapetype/),\
\
[ShapeType::CurvedConnector2](../../shapetype/),\
\
[ShapeType::CurvedConnector3](../../shapetype/),\
\
[ShapeType::CurvedConnector4](../../shapetype/),\
\
[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | 점 단위의 그림 프레임 x 좌표입니다. |
| y | **float** | 점 단위의 그림 프레임 y 좌표입니다. |
| width | **float** | 점 단위의 그림 프레임 너비입니다. |
| height | **float** | 점 단위의 그림 프레임 높이입니다. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 그림 프레임에 표시할 [IPPImage](../../ippimage/)입니다. |

### 반환값

새로 생성된 [IPictureFrame](../../ipictureframe/)입니다.

## 참조

* 열거형 [ShapeType](../../shapetype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPictureFrame](../../ipictureframe/)
* 클래스 [IPPImage](../../ippimage/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)