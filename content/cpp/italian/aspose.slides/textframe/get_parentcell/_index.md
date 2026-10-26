---
title: get_ParentCell()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la cella padre o null se l'oggetto padre non implementa l'interfaccia ICell. Solo lettura ICell.
type: docs
weight: 105
url: /it/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() metodo

Restituisce la cella padre o null se l'oggetto padre non implementa l'interfaccia [ICell](../../icell/). Solamente lettura [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
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
* Classe [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)