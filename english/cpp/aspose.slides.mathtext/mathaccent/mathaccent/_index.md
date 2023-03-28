---
title: MathAccent()
second_title: Aspose.Slides for C++ API Reference
description: Creates a math accent applying to a specified math element with the default accent character value
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>) constructor


Creates a math accent applying to a specified math element with the default accent character value

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | a math element to apply accent |
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## MathAccent::MathAccent([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, char16_t) constructor


Creates a math accent applying to a specified math element

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply accent |
| accentCharacter | char16_t | accent character |
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
