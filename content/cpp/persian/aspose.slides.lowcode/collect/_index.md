---
title: Collect
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک گروه از متدها که برای جمع‌آوری شیءهای مدل از انواع مختلف از Presentation قصد دارد.
type: docs
weight: 1
url: /fa/aspose.slides.lowcode/collect/
---
## Collect کلاس

نمایندگی یک گروه از متدها که برای جمع‌آوری شیءهای مدل از انواع مختلف از [Presentation](../../aspose.slides/presentation/) منظور شده‌اند.

```cpp
class Collect
```

## متدها

| متد | توضیح |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | تمام نمونه‌های [Shape](../../aspose.slides/shape/) را در [Presentation](../../aspose.slides/presentation/) جمع‌آوری می‌کند. |
## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... تغییر قالب‌بندی شکل یا سایر خصوصیات
}
```

## همچنین ببینید

* فضای‌نام [Aspose::Slides::LowCode](../)
* کتابخانه [Aspose.Slides](../../)