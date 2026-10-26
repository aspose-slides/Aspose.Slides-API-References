---
title: AddMathShape()
second_title: Aspose.Slides for C++ API 참조
description: 수학 콘텐츠를 호스팅하기 위한 새로운 사각형 자동 도형을 생성하고 이를 도형 컬렉션의 끝에 추가합니다.
type: docs
weight: 365
url: /ko/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) 메서드

새로운 사각형 자동 도형을 생성하여 수학 콘텐츠를 호스트하고 도형 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 도형 프레임의 x좌표(포인트 단위). |
| y | **float** | 도형 프레임의 y좌표(포인트 단위). |
| width | **float** | 도형 프레임의 너비(포인트 단위). |
| height | **float** | 도형 프레임의 높이(포인트 단위). |

### 반환값

새로 생성된 [IAutoShape](../../iautoshape/).

## 비고

다음 예제는 PowerPoint [Presentation](../../presentation/)에 수학 방정식을 추가하는 방법을 보여줍니다.
```cpp
auto pres = System::MakeObject<Presentation>();

auto mathShape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 720.0f, 150.0f);
auto mathPortion = mathShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);
auto mathParagraph = (System::AsCast<MathPortion>(mathPortion))->get_MathParagraph();
auto fraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathParagraph->Add(System::MakeObject<MathBlock>(fraction));
auto a2 = System::MakeObject<MathematicalText>(u"a")->SetSuperscript(u"2");
auto b2 = System::MakeObject<MathematicalText>(u"b")->SetSuperscript(u"2");
auto c2 = System::MakeObject<MathematicalText>(u"c")->SetSuperscript(u"2");
auto mathBlock = c2->Join(u"=")->Join(a2)->Join(u"+")->Join(b2); // c^2 = a^2 + b^2
mathParagraph->Add(mathBlock);
pres->Save(u"math.pptx", SaveFormat::Pptx);
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)