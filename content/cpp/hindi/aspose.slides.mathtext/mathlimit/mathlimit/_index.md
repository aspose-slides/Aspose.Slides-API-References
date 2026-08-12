---
title: MathLimit()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: MathLimit क्लास का नया उदाहरण प्रारंभ करता है।
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/mathlimit/mathlimit/
---
## MathLimit::MathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) constructor

एक नया [MathLimit](../) क्लास का उदाहरण प्रारंभ करता है।

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)
```

## टिप्पणी

उदाहरण: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"), false);
```

## MathLimit::MathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor

निचली सीमा के साथ एक नया [MathLimit](../) क्लास का उदाहरण प्रारंभ करता है।

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)
```

## टिप्पणी

उदाहरण: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"));
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathLimit](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)