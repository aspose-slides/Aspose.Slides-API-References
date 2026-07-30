---
title: get_Name()
second_title: Aspose.Slides pro referenci API C++
description: Název funkce Například názvy funkcí jsou sin a cos
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() metoda

Název funkce Například názvy funkcí jsou sin a cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
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
* Třída [IMathFunction](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)