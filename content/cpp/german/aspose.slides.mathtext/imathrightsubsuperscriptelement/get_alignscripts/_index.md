---
title: get_AlignScripts()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt die Ausrichtung von Tiefstellung/Hochstellung an. Wenn true, sind Tiefstellung und Hochstellung horizontal zueinander ausgerichtet. Wenn false, werden sie an die Form der Basis angepasst. Der Standardwert ist false.
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() Methode

Gibt die Ausrichtung von Tiefstellung/Hochstellung an. Wenn true, sind Tiefstellung und Hochstellung horizontal zueinander ausgerichtet. Wenn false, werden sie an die Form der Basis angepasst. Der Standardwert ist false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
```

## Hinweise

Beispiel:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Siehe auch

* Klasse [IMathRightSubSuperscriptElement](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)