---
title: SplitTextByColumns()
second_title: Referencia de API de Aspose.Slides para C++
description: Divide el contenido de texto del ITextFrame en una matriz de cadenas, donde cada elemento corresponde a una columna de texto separada dentro del marco.
type: docs
weight: 144
url: /es/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() método


Divide el contenido de texto del [ITextFrame](../../itextframe/) en una matriz de cadenas, 

 donde cada elemento corresponde a una columna de texto separada dentro del marco.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```


### Valor devuelto

Una matriz de cadenas, donde cada cadena representa el contenido de texto de una columna específica 

 en el [ITextFrame](../../itextframe/).
## Observaciones



Si el marco de texto no contiene varias columnas, la matriz devuelta tendrá un solo elemento 

 conteniendo todo el texto. 

 Las columnas vacías se representarán como cadenas vacías en la matriz. 

El siguiente ejemplo muestra cómo usar [TextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Obtenga la primera forma en la diapositiva y conviértala a ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Divida el contenido del marco de texto en columnas
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Imprima el texto de cada columna en la consola
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [TextFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)