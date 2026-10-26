---
title: get_ParentCell()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la celda padre o null si el objeto padre no implementa la interfaz ICell. Sólo lectura ICell.
type: docs
weight: 79
url: /es/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() method


Devuelve la celda padre o null si el objeto padre no implementa la [ICell](../../icell/) interface. Sólo lectura [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Observaciones


El siguiente fragmento de código muestra 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ICell](../../icell/)
* Clase [ITextFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)