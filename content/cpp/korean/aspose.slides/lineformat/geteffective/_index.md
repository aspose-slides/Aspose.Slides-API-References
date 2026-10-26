---
title: GetEffective()
second_title: Aspose.Slides C++ API 레퍼런스
description: 상속이 적용된 효과적인 라인 서식 데이터를 가져옵니다.
type: docs
weight: 417
url: /ko/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() 메서드


상속이 적용된 효과적인 라인 서식 데이터를 가져옵니다.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```


### 반환값

하나의 [ILineFormatEffectiveData](../../ilineformateffectivedata/).

## 비고



이 예제는 도형의 효과적인 라인 서식 속성을 가져오는 방법을 보여줍니다.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## 관련

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* 클래스 [LineFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)