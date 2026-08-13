---
title: InsertPictureFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.
type: docs
weight: 456
url: /ko/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) 메서드

지정된 이미지를 포함하는 새로운 그림 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 그림 프레임을 삽입할 0부터 시작하는 인덱스. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/)에 포함된 shape type을 지정합니다. 단, 모든 종류의 선은 제외됩니다:<br>[ShapeType::Line](../../shapetype/),<br>[ShapeType::StraightConnector1](../../shapetype/),<br>[ShapeType::BentConnector2](../../shapetype/),<br>[ShapeType::BentConnector3](../../shapetype/),<br>[ShapeType::BentConnector4](../../shapetype/),<br>[ShapeType::BentConnector5](../../shapetype/),<br>[ShapeType::CurvedConnector2](../../shapetype/),<br>[ShapeType::CurvedConnector3](../../shapetype/),<br>[ShapeType::CurvedConnector4](../../shapetype/),<br>[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | 그림 프레임의 x 좌표, 포인트 단위. |
| y | **float** | 그림 프레임의 y 좌표, 포인트 단위. |
| width | **float** | 그림 프레임의 너비, 포인트 단위. |
| height | **float** | 그림 프레임의 높이, 포인트 단위. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 그림 프레임에 표시할 [IPPImage](../../ippimage/). |

### 반환 값

새로 생성된 [IPictureFrame](../../ipictureframe/).

## 참조

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPictureFrame](../../ipictureframe/)
* 클래스 [IPPImage](../../ippimage/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)