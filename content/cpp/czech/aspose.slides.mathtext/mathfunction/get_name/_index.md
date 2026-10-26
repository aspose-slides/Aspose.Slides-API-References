---
title: get_Name()
second_title: Aspose.Slides pro C++ API Reference
description: Název funkce Například názvy funkcí jsou sin a cos
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() metoda


Název funkce Pro příklad, názvy funkcí jsou sin a cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## Poznámky


Příklad: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathFunction](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)