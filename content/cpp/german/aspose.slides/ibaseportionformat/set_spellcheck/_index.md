---
title: set_SpellCheck()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung zulässig. Der Standardwert ist false.
type: docs
weight: 612
url: /de/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) Methode

Setzt einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung zulässig. Der Standardwert ist **false**.

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## Bemerkungen

Das folgende Beispiel zeigt das Aktivieren des SpellCheck-Flags vor dem Speichern der Präsentation:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Greift auf den ersten Textabschnitt im ersten Shape der ersten Folie zu
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Aktiviert die Rechtschreibprüfung für diesen Textabschnitt
portion->get_PortionFormat()->set_SpellCheck(true);
// Speichert die geänderte Präsentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [IBasePortionFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)