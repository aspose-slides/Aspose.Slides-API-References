---
title: AddPictureFrame()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 이를 모양 컬렉션의 끝에 추가합니다.
type: docs
weight: 404
url: /ko/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) 메서드

지정된 이미지를 포함하는 새 그림 프레임을 생성하고 이를 모양 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 모든 종류의 선을 제외하고 [ShapeType](../../shapetype/)에 포함된 모양 유형을 지정합니다: [ShapeType::Line](../../shapetype/), [ShapeType::StraightConnector1](../../shapetype/), [ShapeType::BentConnector2](../../shapetype/), [ShapeType::BentConnector3](../../shapetype/), [ShapeType::BentConnector4](../../shapetype/), [ShapeType::BentConnector5](../../shapetype/), [ShapeType::CurvedConnector2](../../shapetype/), [ShapeType::CurvedConnector3](../../shapetype/), [ShapeType::CurvedConnector4](../../shapetype/), [ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | 그림 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 그림 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 그림 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 그림 프레임의 높이(포인트 단위)입니다. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/)을(를) 그림 프레임에 표시합니다. |

### 반환값

새로 생성된 [IPictureFrame](../../ipictureframe/)입니다.

## 참조

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)