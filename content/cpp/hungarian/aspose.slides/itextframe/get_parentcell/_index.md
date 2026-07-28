---
title: get_ParentCell()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a szülő cellát, vagy null értéket, ha a szülő objektum nem valósítja meg az ICell interfészt. Csak olvasható ICell.
type: docs
weight: 79
url: /hu/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() metódus


A szülő cellát vagy null értéket ad vissza, ha a szülő objektum nem valósítja meg a [ICell](../../icell/) interfészt. Csak olvasható [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Megjegyzések


A következő kódrészlet mutatja 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ICell](../../icell/)
* Osztály [ITextFrame](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)