---
title: get_Base()
second_title: Aspose.Slides für C++ API-Referenz
description: Das Argument, auf das der Akzent angewendet wurde
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() Methode

Das Argument, auf das der Akzent angewendet wurde

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## Hinweise

Beispiel: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathAccent](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)