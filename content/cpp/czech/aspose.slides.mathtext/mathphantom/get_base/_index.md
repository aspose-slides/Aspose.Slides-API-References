---
title: get_Base()
second_title: Aspose.Slides pro C++ API Reference
description: Argument Base
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() metoda


Argument Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathPhantom](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)