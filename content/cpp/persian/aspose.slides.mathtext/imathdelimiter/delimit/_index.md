---
title: Delimit()
second_title: Aspose.Slides برای C++ راهنمای API
description: آرگومان‌ها را با استفاده از کاراکتر تعیین‌شده جدا می‌کند
type: docs
weight: 144
url: /fa/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) متد

آرگومان‌ها را با استفاده از کاراکتر جداکنندهٔ مشخص محدود می‌کند

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char16_t | کاراکتر جداکننده |

### Return Value

این شی پس از اعمال کاراکتر جداکننده

## Remarks



مثال: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## See Also

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)