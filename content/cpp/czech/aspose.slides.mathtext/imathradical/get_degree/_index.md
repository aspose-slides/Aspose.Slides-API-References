---
title: get_Degree()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Argument stupně
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() method

Argument stupně

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Poznámky

Příklad:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // kubický kořen
auto degreeElem = radical->get_Degree();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathRadical](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)