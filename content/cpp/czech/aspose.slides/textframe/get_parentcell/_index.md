---
title: get_ParentCell()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací nadřazenou buňku nebo null, pokud nadřazený objekt neimplementuje rozhraní ICell. Pouze pro čtení ICell.
type: docs
weight: 105
url: /cs/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() metoda

Vrací nadřízenou buňku nebo null, pokud nadřazený objekt neimplementuje rozhraní [ICell](../../icell/). Pouze pro čtení [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## Poznámky

Následující ukázka kódu ukazuje 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ICell](../../icell/)
* Třída [TextFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)