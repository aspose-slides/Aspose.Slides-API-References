---
title: get_Arguments()
second_title: Aspose.Slides för C++ API-referens
description: Ett eller flera matematiska element separerade med avgränsartecken
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() metod


Ett eller flera matematiska element separerade med avgränsartecken

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## Anmärkningar


Exempel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElementCollection](../../imathelementcollection/)
* Klass [IMathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)