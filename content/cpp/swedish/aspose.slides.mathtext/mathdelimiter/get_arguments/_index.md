---
title: get_Arguments()
second_title: Aspose.Slides för C++ API-referens
description: En eller flera matematiska element separerade av avgränsartecken
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() metod

En eller flera matematiska element separerade av avgränsartecken

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## Anmärkningar

Exempel:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [IMathElementCollection](../../imathelementcollection/)
* klass [MathDelimiter](../)
* namnrymd [Aspose::Slides::MathText](../../)
* bibliotek [Aspose.Slides](../../../)