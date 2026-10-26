---
title: get_ParentCell()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die übergeordnete Zelle zurück oder null, wenn das übergeordnete Objekt das ICell Interface nicht implementiert. Schreibgeschützt ICell.
type: docs
weight: 79
url: /de/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() Methode


Gibt die übergeordnete Zelle zurück oder null, wenn das übergeordnete Objekt das [ICell](../../icell/) Interface nicht implementiert. Schreibgeschützt [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Anmerkungen


Das folgende Codebeispiel zeigt 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICell](../../icell/)
* Klasse [ITextFrame](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)