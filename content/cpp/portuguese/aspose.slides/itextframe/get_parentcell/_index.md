---
title: get_ParentCell()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a célula pai ou null se o objeto pai não implementar a interface ICell. Somente leitura ICell.
type: docs
weight: 79
url: /pt/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() método

Retorna a célula pai ou null se o objeto pai não implementar a interface [ICell](../../icell/). Somente leitura [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Observações

O exemplo de código a seguir mostra
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICell](../../icell/)
* Classe [ITextFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)