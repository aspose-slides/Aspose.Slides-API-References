---
title: get_Degree()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Argument stupně
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() metoda


Argument Degree

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Poznámky


Příklad: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathRadical](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)