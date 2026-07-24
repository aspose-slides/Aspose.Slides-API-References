---
title: set_SpellCheck()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt einen Wert fest, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt wird, ist die Rechtschreibprüfung erlaubt. Der Standardwert ist false.
type: docs
weight: 612
url: /de/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) Methode

Setzt einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt wird, ist die Rechtschreibprüfung zulässig. Der Standardwert ist **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## Hinweise

Das folgende Beispiel demonstriert das Aktivieren des SpellCheck-Flags vor dem Speichern der Präsentation:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
portion->get_PortionFormat()->set_SpellCheck(true);
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [BasePortionFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)