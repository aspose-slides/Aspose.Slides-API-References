---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Argumentet till vilket accenten tillämpades
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() metod


Argumentet till vilket accenten tillämpades

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## Anmärkningar


Exempel:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathAccent](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)