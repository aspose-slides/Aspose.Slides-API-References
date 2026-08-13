---
title: get_Rewind()
second_title: Aspose.Slides for C++ API 참조
description: 이 속성은 효과가 재생을 마쳤을 때 되감기를 할지 여부를 지정합니다. 읽기 bool.
type: docs
weight: 235
url: /ko/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() 메서드


이 속성은 효과가 재생을 마쳤을 때 되감기를 할지 여부를 지정합니다. 읽기 **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 첫 번째 슬라이드의 효과 시퀀스를 가져옵니다
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// 메인 시퀀스의 첫 번째 효과를 가져옵니다.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// 효과의 Timing/Rewind를 켭니다.
effect->get_Timing()->set_Rewind(true);
```

## 참조

* 클래스 [Timing](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)