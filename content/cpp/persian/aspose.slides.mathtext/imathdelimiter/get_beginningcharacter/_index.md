---
title: get_BeginningCharacter()
second_title: مرجع API Aspose.Slides برای C++
description: "کاراکتر شروع جداکننده، ابتدا یا کاراکتر بازشونده جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای محاطی مانند پرانتز، کروشه و آکولاد هستند. مقدار پیش‌فرض: '('."
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() متد

کاراکتر شروع جداکننده، ابتدا یا کاراکتر بازشونده جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای محاطی مانند پرانتز، کروشه و آکولاد هستند. مقدار پیش‌فرض: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## توضیحات

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## موارد مرتبط

* کلاس [IMathDelimiter](../)
* فضای نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)