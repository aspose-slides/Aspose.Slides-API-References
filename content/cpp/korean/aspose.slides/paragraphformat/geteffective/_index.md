---
title: GetEffective()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 상속이 적용된 효과적인 단락 서식 데이터를 가져옵니다.
type: docs
weight: 365
url: /ko/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() 메서드


상속이 적용된 효과적인 단락 서식 데이터를 가져옵니다.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### 반환 값

다음 [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## 비고



이 예제에서는 일부 효과적인 단락 서식 속성을 가져오는 방법을 보여줍니다. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* 클래스 [ParagraphFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)