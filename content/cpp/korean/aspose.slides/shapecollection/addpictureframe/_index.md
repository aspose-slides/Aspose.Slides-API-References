---
title: AddPictureFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 이를 shape 컬렉션의 끝에 추가합니다.
type: docs
weight: 443
url: /ko/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) 메서드

지정된 이미지를 포함하는 새 그림 프레임을 생성하고 이를 shape 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/)에 포함된 도형 유형을 지정합니다. 단, 모든 종류의 선은 제외합니다:<br>[ShapeType::Line](../../shapetype/),<br>[ShapeType::StraightConnector1](../../shapetype/),<br>[ShapeType::BentConnector2](../../shapetype/),<br>[ShapeType::BentConnector3](../../shapetype/),<br>[ShapeType::BentConnector4](../../shapetype/),<br>[ShapeType::BentConnector5](../../shapetype/),<br>[ShapeType::CurvedConnector2](../../shapetype/),<br>[ShapeType::CurvedConnector3](../../shapetype/),<br>[ShapeType::CurvedConnector4](../../shapetype/),<br>[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | picture frame의 x 좌표(포인트). |
| y | **float** | picture frame의 y 좌표(포인트). |
| width | **float** | picture frame의 너비(포인트). |
| height | **float** | picture frame의 높이(포인트). |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | picture frame에 표시할 [IPPImage](../../ippimage/). |

### 반환값

새로 생성된 [IPictureFrame](../../ipictureframe/).

## 참고

* 열거형 [ShapeType](../../shapetype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPictureFrame](../../ipictureframe/)
* 클래스 [IPPImage](../../ippimage/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)