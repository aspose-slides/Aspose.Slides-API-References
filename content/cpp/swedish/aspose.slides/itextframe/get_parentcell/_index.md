---
title: get_ParentCell()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar den överordnade cellen eller null om det överordnade objektet inte implementerar ICell-gränssnittet. Skrivskyddad ICell.
type: docs
weight: 79
url: /sv/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() metod


Returnerar den överordnade cellen eller null om det överordnade objektet inte implementerar [ICell](../../icell/)-gränssnittet. Skrivskyddad [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Anmärkningar


Följande kodexempel visar 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ICell](../../icell/)
* Klass [ITextFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)