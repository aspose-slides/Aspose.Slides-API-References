---
title: MathAccent()
second_title: مرجع API Aspose.Slides برای C++
description: یک اکسنت ریاضی ایجاد می‌کند که بر روی یک عنصر ریاضی مشخص اعمال می‌شود با مقدار پیش‌فرض کاراکتر اکسنت
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) سازنده

یک اکسنت ریاضی ایجاد می‌کند که بر روی یک عنصر ریاضی مشخص اعمال می‌شود با مقدار پیش‌فرض کاراکتر اکسنت

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | یک عنصر ریاضی برای اعمال اکسنت |
| accentCharacter | char16_t | کاراکتر اکسنت |
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) سازنده

یک اکسنت ریاضی ایجاد می‌کند که بر روی یک عنصر ریاضی مشخص اعمال می‌شود

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی برای اعمال اکسنت |
| accentCharacter | char16_t | کاراکتر اکسنت |
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathAccent](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)