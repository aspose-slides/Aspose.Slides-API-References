---
title: AddConnector()
second_title: Aspose.Slides for C++ API 참조
description: 기본 템플릿 스타일이 적용된 새로운 커넥터 모양을 만들고 이를 모양 컬렉션의 끝에 추가합니다.
type: docs
weight: 417
url: /ko/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) 메서드

새 기본 템플릿 스타일이 적용된 커넥터 모양을 만들고 이를 모양 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 추가할 커넥터 모양의 [ShapeType](../../shapetype/) |
| x | **float** | 커넥터 프레임의 x 좌표(포인트 단위) |
| y | **float** | 커넥터 프레임의 y 좌표(포인트 단위) |
| width | **float** | 커넥터 프레임의 너비(포인트 단위) |
| height | **float** | 커넥터 프레임의 높이(포인트 단위) |

### 반환값

새로 만든 [IConnector](../../iconnector/).

## 비고

다음 예제는 PowerPoint [Presentation](../../presentation/)에서 두 모양(타원과 사각형) 사이에 커넥터(굽은 커넥터)를 추가하는 방법을 보여줍니다.

```cpp
// PPTX 파일을 나타내는 프레젠테이션 클래스를 인스턴스화합니다
auto input = System::MakeObject<Presentation>();

// 특정 슬라이드의 도형 컬렉션에 접근합니다
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// 타원 자동 도형을 추가합니다
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// 사각형 자동 도형을 추가합니다
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// 슬라이드 도형 컬렉션에 커넥터 도형을 추가합니다
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// 커넥터를 사용하여 도형들을 연결합니다
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// 도형들 사이의 자동 최단 경로를 설정하는 reroute를 호출합니다
connector->Reroute();

// 프레젠테이션을 저장합니다
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) 메서드

새 커넥터 모양을 만들고 이를 모양 컬렉션의 끝에 추가합니다. 필요에 따라 기본 템플릿 스타일을 적용할 수 있습니다.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 생성할 커넥터 모양의 [ShapeType](../../shapetype/) |
| x | **float** | 커넥터 프레임의 x 좌표(포인트 단위) |
| y | **float** | 커넥터 프레임의 y 좌표(포인트 단위) |
| width | **float** | 커넥터 프레임의 너비(포인트 단위) |
| height | **float** | 커넥터 프레임의 높이(포인트 단위) |
| createFromTemplate | **bool** | 기본 템플릿 스타일(이름이 비어 있지 않고 단순 스타일)을 적용하려면 true, 기본 속성 값으로 커넥터를 만들려면 false |

### 반환값

새로 만든 [IConnector](../../iconnector/).

## 참고

* 열거형 [ShapeType](../../shapetype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IConnector](../../iconnector/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)