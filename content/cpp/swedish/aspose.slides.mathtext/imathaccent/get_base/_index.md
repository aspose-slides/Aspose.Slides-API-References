---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Argumentet som accenten applicerades på
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() metod


Argumentet som accenten applicerades på

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
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
* Klass [IMathAccent](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)