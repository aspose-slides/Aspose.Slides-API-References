---
title: MathAccent()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ تمييزًا رياضيًا يُطبق على عنصر رياضي محدد باستخدام قيمة حرف التمييز الافتراضية
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) منشئ

يقوم بإنشاء تمييز رياضي يُطبق على عنصر رياضي محدد باستخدام قيمة حرف التمييز الافتراضية

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```

### معلمات

| معاملة | نوع | وصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر رياضي لتطبيق التمييز |
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) منشئ

يقوم بإنشاء تمييز رياضي يُطبق على عنصر رياضي محدد

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```

### معلمات

| معاملة | نوع | وصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر رياضي لتطبيق التمييز |
| accentCharacter | char16_t | حرف التمييز |
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathAccent](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)