---
title: get_SeparatorCharacter()
second_title: Aspose.Slides für C++ API-Referenz
description: "Delimiter Separator Character gibt das Zeichen an, das die Argumente im Delimiter-Objekt trennt. Der Standardwert ist: '|'."
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() Methode

Delimiter Separator Character gibt das Zeichen an, das die Argumente im Delimiter-Objekt trennt. Der Standardwert ist: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
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