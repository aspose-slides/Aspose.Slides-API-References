---
title: get_SpellCheck()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt einen Wert zurück, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Der Standardwert ist false.
type: docs
weight: 599
url: /de/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() Methode


Gibt einen Wert zurück, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Der Standardwert ist **false**.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## Hinweise


Das folgende Beispiel demonstriert das Aktivieren des SpellCheck-Flags vor dem Speichern der Präsentation:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [BasePortionFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)