---
title: get_ParentCell()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la celda padre o null si el objeto padre no implementa la interfaz ICell. Solo lectura ICell.
type: docs
weight: 105
url: /es/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() método

Devuelve la celda padre o null si el objeto padre no implementa la interfaz [ICell](../../icell/). Solo lectura [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## Observaciones

El siguiente ejemplo de código muestra 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ICell](../../icell/)
* Clase [TextFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)