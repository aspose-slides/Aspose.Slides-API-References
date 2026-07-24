---
title: set_SeparatorCharacter()
second_title: Aspose.Slides für C++ API Referenz
description: "Delimiter Separator Character gibt das Zeichen an, das die Argumente im Delimiter-Objekt trennt. Der Standardwert: '|'."
type: docs
weight: 53
url: /de/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) Methode


Delimiter Separator Character gibt das Zeichen an, das die Argumente im Delimiter-Objekt trennt. Der Standardwert: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## Hinweise


Beispiel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Siehe auch

* Klasse [IMathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)