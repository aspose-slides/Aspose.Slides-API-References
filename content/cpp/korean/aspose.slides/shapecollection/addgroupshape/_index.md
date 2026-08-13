---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API 참조
description: 새로운 빈 그룹 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. 그룹\u2019s 프레임은 추가된 모든 도형에 맞게 자동으로 조정됩니다.
type: docs
weight: 391
url: /ko/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() method

새로운 빈 그룹 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. 그룹\\u2019s 프레임은 추가된 모든 도형에 맞게 자동으로 조정됩니다.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### 반환 값

새로 생성된 [IGroupShape](../../igroupshape/).

## 비고

다음 예시는 PowerPoint [Presentation](../../presentation/) 슬라이드에 그룹 도형을 추가하는 방법을 보여줍니다.
```cpp
// Presentation 클래스 인스턴스화
auto pres = System::MakeObject<Presentation>();

// 첫 번째 슬라이드 가져오기
auto slide = pres->get_Slides()->idx_get(0);
// 슬라이드의 도형 컬렉션에 접근
auto slideShapes = slide->get_Shapes();
// 슬라이드에 그룹 도형 추가
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// 추가된 그룹 도형 내부에 도형 추가
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// 그룹 도형 프레임 추가
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// PPTX 파일을 디스크에 저장
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) method

새로운 그룹 도형을 생성하고, 지정된 SVG 이미지를 개별 도형으로 변환한 뒤, 결과 그룹을 도형 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/)은 벡터 콘텐츠를 포함하며 도형으로 변환됩니다. |
| x | **float** | 그룹\\u2019s 프레임의 x 좌표(포인트 단위). |
| y | **float** | 그룹\\u2019s 프레임의 y 좌표(포인트 단위). |
| width | **float** | 그룹\\u2019s 프레임의 너비(포인트 단위). |
| height | **float** | 그룹\\u2019s 프레임의 높이(포인트 단위). |

### 반환 값

새로 생성된 [IGroupShape](../../igroupshape/).

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IGroupShape](../../igroupshape/)
* 클래스 [ShapeCollection](../)
* 클래스 [ISvgImage](../../isvgimage/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)