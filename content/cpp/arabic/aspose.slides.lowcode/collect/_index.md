---
title: Collect
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يمثل مجموعة من الأساليب المصممة لجمع كائنات النموذج من أنواع مختلفة من Presentation.
type: docs
weight: 1
url: /ar/aspose.slides.lowcode/collect/
---
## Collect فئة


يمثل مجموعة من الأساليب المصممة لجمع كائنات النموذج من أنواع مختلفة من [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | يجمع جميع المثيلات من [Shape](../../aspose.slides/shape/) في الـ [Presentation](../../aspose.slides/presentation/). |
## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... تغيير تنسيق الشكل أو خصائص أخرى
}
```

## انظر أيضًا

* نطاق [Aspose::Slides::LowCode](../)
* مكتبة [Aspose.Slides](../../)