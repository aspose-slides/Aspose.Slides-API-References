---
title: MathematicalText()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "منشئ افتراضي (إنشاء قيمة String::Empty)"
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() منشئ


منشئ افتراضي (إنشاء قيمة String::Empty)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## ملاحظات


مثال: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) منشئ


إنشاء [MathText](../../) برمز واحد

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathSymbol | char16_t | رمز واحد |
## ملاحظات



مثال: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) منشئ


إنشاء [MathematicalText](../) من النص

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | قيمة النص |
## ملاحظات



مثال: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) منشئ


إنشاء [MathematicalText](../) من النص وإعدادات التنسيق

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | قيمة النص |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | إعدادات تنسيق النص |
## ملاحظات



مثال: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [MathematicalText](../)
* الفئة [String](../../../system/string/)
* الفئة [IPortionFormat](../../../aspose.slides/iportionformat/)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)