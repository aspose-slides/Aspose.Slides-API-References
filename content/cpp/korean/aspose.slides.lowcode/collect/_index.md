---
title: Collect
second_title: Aspose.Slides for C++ API 레퍼런스
description: Presentation에서 다양한 유형의 모델 객체를 수집하도록 설계된 메서드 그룹을 나타냅니다.
type: docs
weight: 1
url: /ko/aspose.slides.lowcode/collect/
---
## Collect 클래스


다양한 유형의 모델 객체를 [Presentation](../../aspose.slides/presentation/)에서 수집하도록 설계된 메서드 그룹을 나타냅니다.

```cpp
class Collect
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | [Presentation](../../aspose.slides/presentation/)에서 [Shape](../../aspose.slides/shape/)의 모든 인스턴스를 수집합니다. |
## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... shape 서식을 변경하거나 기타 속성을 변경합니다
}
```

## 참고

* 네임스페이스 [Aspose::Slides::LowCode](../)
* 라이브러리 [Aspose.Slides](../../)