---
title: get_Base()
second_title: Aspose.Slides für C++ API-Referenz
description: Base Argument
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathphantom/get_base/
---
## IMathPhantom::get_Base() Methode


Base Argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathPhantom::get_Base()=0
```

## Hinweise


Beispiel:
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathPhantom](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)