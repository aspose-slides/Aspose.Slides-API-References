---
title: set_AlignScripts()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Ausrichtung von Unter- und Hochstellung an. Wenn true, sind Unter- und Hochstellung horizontal zueinander ausgerichtet. Wenn false, werden sie an die Form der Basis angepasst. Der Standardwert ist false.
type: docs
weight: 53
url: /de/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) Methode

Gibt die Ausrichtung von Unter- und Hochstellung an. Wenn true, sind Unter- und Hochstellung horizontal zueinander ausgerichtet. Wenn false, werden sie an die Form der Basis angepasst. Standardwert ist false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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
* Library [Aspose.Slides](../../../)