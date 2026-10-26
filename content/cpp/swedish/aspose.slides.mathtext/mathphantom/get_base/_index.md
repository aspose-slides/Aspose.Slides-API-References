---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Base-argument
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() metod

Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
```

## Anmärkningar

Exempel: 
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathPhantom](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)