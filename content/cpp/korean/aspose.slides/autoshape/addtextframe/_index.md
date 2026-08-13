---
title: AddTextFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 TextFrame을 도형에 추가합니다. 도형에 이미 TextFrame이 있는 경우 텍스트를 단순히 변경합니다.
type: docs
weight: 66
url: /ko/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) 메서드

새로운 [TextFrame](../../textframe/)를 도형에 추가합니다. 도형에 이미 [TextFrame](../../textframe/)가 있는 경우 단순히 텍스트를 변경합니다.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 새로운 [TextFrame](../../textframe/)의 기본 텍스트. |
## 비고

다음 샘플 코드는 PowerPoint [Presentation](../../presentation/)에 워터마크 텍스트를 추가하는 방법을 보여줍니다.
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
다음 예제는 [Slide](../../slide/)에 텍스트 상자를 만드는 방법을 보여줍니다.
```cpp
// 프레젠테이션 인스턴스화
auto pres = System::MakeObject<Presentation>();

// 프레젠테이션의 첫 번째 슬라이드 가져오기
auto slide = pres->get_Slides()->idx_get(0);
// 타입이 Rectangle로 설정된 AutoShape 추가
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Rectangle에 TextFrame 추가
shape->AddTextFrame(u" ");
// 텍스트 프레임에 접근
auto txtFrame = shape->get_TextFrame();
// 텍스트 프레임용 Paragraph 객체 생성
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Paragraph용 Portion 객체 생성
auto portion = para->get_Portions()->idx_get(0);
// 텍스트 설정
portion->set_Text(u"Aspose TextBox");
// 프레젠테이션을 디스크에 저장
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
다음 예제는 텍스트 상자에 열을 추가하는 방법을 보여줍니다.
```cpp
auto presentation = System::MakeObject<Presentation>();

// 프레젠테이션의 첫 번째 슬라이드 가져오기
auto slide = presentation->get_Slides()->idx_get(0);
// 타입이 Rectangle로 설정된 AutoShape 추가
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Rectangle에 TextFrame 추가
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// TextFrame의 텍스트 형식 가져오기
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// TextFrame의 열 수 지정
format->set_ColumnCount(3);
// 열 사이 간격 지정
format->set_ColumnSpacing(10);
// 프레젠테이션 저장
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ITextFrame](../../itextframe/)
* 클래스 [String](../../../system/string/)
* 클래스 [AutoShape](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)