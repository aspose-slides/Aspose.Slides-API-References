---
title: Collect
second_title: Aspose.Slides for C++ API Reference
description: Represents a group of methods intended to collect model objects of different types from Presentation.
type: docs
weight: 1
url: /aspose.slides.lowcode/collect/
---
## Collect class


Represents a group of methods intended to collect model objects of different types from [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## Methods

| Method | Description |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Collects all instances of [Shape](../../aspose.slides/shape/) in the [Presentation](../../aspose.slides/presentation/). |
## Remarks



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... change shape formatting or other properties
}
```

## See Also

* Namespace [Aspose::Slides::LowCode](../)
* Library [Aspose.Slides](../../)