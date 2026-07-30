---
title: get_ParentCell()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací nadřazenou buňku nebo null, pokud nadřazený objekt neimplementuje rozhraní ICell. Pouze pro čtení ICell.
type: docs
weight: 79
url: /cs/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() metoda


Vrací rodičovskou buňku nebo null, pokud rodičovský objekt neimplementuje rozhraní [ICell](../../icell/). Pouze pro čtení [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Poznámky


Následující ukázkový kód ukazuje 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ICell](../../icell/)
* Třída [ITextFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)