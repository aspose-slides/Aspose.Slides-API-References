---
title: get_Base()
second_title: Aspose.Slides pro C++ – reference API
description: Základní argument
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathphantom/get_base/
---
## IMathPhantom::get_Base() metoda

Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathPhantom::get_Base()=0
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
* Třída [IMathPhantom](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)