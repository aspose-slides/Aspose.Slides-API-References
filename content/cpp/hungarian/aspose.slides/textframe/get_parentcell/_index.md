---
title: get_ParentCell()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a szülőcellát, vagy null értéket, ha a szülőobjektum nem valósítja meg az ICell interfészt. Csak olvasható ICell.
type: docs
weight: 105
url: /hu/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() metódus

Visszaadja a szülőcellát, vagy null értéket, ha a szülőobjektum nem valósítja meg a [ICell](../../icell/) interfész. Csak olvasható [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## Megjegyzések

Az alábbi kódrészlet bemutatja
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICell](../../icell/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)