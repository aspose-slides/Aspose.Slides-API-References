---
title: get_ParentCell()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la cella padre o null se l'oggetto padre non implementa l'interfaccia ICell. Solo lettura ICell.
type: docs
weight: 79
url: /it/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() metodo


Restituisce la cella padre o null se l'oggetto padre non implementa l'interfaccia [ICell](../../icell/). Solo lettura [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Osservazioni


Il seguente esempio di codice mostra
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICell](../../icell/)
* Classe [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)