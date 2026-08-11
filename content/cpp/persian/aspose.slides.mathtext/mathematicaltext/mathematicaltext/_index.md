---
title: MathematicalText()
second_title: مرجع API Aspose.Slides برای C++
description: "سازنده پیش‌فرض (ایجاد مقدار String::Empty)"
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() سازنده

سازنده پیش‌فرض (ایجاد String::Empty Value)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## توضیحات

مثال:
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) سازنده

ایجاد [MathText](../../) با یک نماد

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathSymbol | char16_t | نماد تک |

## توضیحات

مثال:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) سازنده

ایجاد [MathematicalText](../) از متن

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | مقدار متن |

## توضیات

مثال:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) سازنده

ایجاد [MathematicalText](../) از متن و تنظیمات قالب

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | مقدار متن |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | تنظیمات قالب متن |

## توضیحات

مثال:
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [MathematicalText](../)
* کلاس [String](../../../system/string/)
* کلاس [IPortionFormat](../../../aspose.slides/iportionformat/)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)