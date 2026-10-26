---
title: get_ParentCell()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de bovenliggende cel of null als het bovenliggende object de ICell interface niet implementeert. Alleen-lezen ICell.
type: docs
weight: 79
url: /nl/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() method


Retourneert de bovenliggende cel of null als het bovenliggende object de [ICell](../../icell/) interface niet implementeert. Alleen-lezen [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Opmerkingen


Het volgende codevoorbeeld toont 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICell](../../icell/)
* Klasse [ITextFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)