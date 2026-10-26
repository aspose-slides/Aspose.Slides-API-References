---
title: SplitTextByColumns()
second_title: Referencia de la API de Aspose.Slides para C++
description: Divide el contenido de texto del ITextFrame en una matriz de cadenas, donde cada elemento corresponde a una columna de texto separada dentro del marco.
type: docs
weight: 118
url: /es/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() método


Divide el contenido de texto del [ITextFrame](../) en una matriz de cadenas, 

 donde cada elemento corresponde a una columna de texto separada dentro del marco.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### Valor devuelto

Una matriz de cadenas, donde cada cadena representa el contenido de texto de una columna específica 

 en el [ITextFrame](../).
## Observaciones



Si el marco de texto no contiene varias columnas, la matriz devuelta tendrá un solo elemento 

 que contiene el texto completo. 

 Las columnas vacías se representarán como cadenas vacías en la matriz. 

El siguiente ejemplo demuestra cómo usar [ITextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Obtener la primera forma en la diapositiva y convertirla a ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Dividir el contenido del marco de texto en columnas
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Imprimir el texto de cada columna en la consola
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [ITextFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)