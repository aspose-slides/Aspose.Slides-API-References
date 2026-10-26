---
title: get_SpellCheck()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt einen Wert zurück, der anzeigt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Der Standardwert ist false.
type: docs
weight: 599
url: /de/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() Methode

Gibt einen Wert zurück, der anzeigt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf **false** gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf **true** gesetzt ist, ist die Rechtschreibprüfung erlaubt. Der Standardwert ist **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## Bemerkungen

Das folgende Beispiel zeigt, wie das SpellCheck-Flag vor dem Speichern der Präsentation aktiviert wird:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Greifen Sie auf den ersten Textabschnitt in der ersten Form auf der ersten Folie zu
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Rechtschreibprüfung für diesen Textabschnitt aktivieren
portion->get_PortionFormat()->set_SpellCheck(true);
// Speichern Sie die geänderte Präsentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [IBasePortionFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)