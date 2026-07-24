---
title: get_Format()
second_title: Aspose.Slides für C++ API-Referenz
description: Textformatierungseigenschaften
type: docs
weight: 27
url: /de/aspose.slides.mathtext/imathematicaltext/get_format/
---
## IMathematicalText::get_Format() Methode


Textformatierungseigenschaften

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::IMathematicalText::get_Format()=0
```

## Anmerkungen


Beispiel:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## Siehe auch

* Typedefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IPortionFormat](../../../aspose.slides/iportionformat/)
* Klasse [IMathematicalText](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)