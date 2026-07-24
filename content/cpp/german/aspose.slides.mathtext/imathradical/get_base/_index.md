---
title: get_Base()
second_title: Aspose.Slides für C++ API-Referenz
description: Base-Argument
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() Methode


Base Argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## Hinweise


Beispiel: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // Kubikwurzel
auto baseElem = radical->get_Base();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathRadical](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)