---  
title: LinkPathRelative
second_title: Referencia de API de Aspose.Slides para .NET  
description: Devuelve la ruta relativa a un archivo vinculado si está presente; de lo contrario, devuelve una cadena vacía. Solo lectura String.
type: docs  
weight: 90  
url: /es/aspose.slides/oleobjectframe/linkpathrelative/
---  
  
## OleObjectFrame.LinkPathRelative property  
  
Devuelve la ruta relativa a un archivo vinculado si está presente; de lo contrario, devuelve una cadena vacía. Solo lectura String.  
  
```csharp  
public string LinkPathRelative { get; }  
```  
  
### Remarks  
  
En las presentaciones de Ppt, algunos enlaces de objetos Ole pueden tener una representación relativa.  
  
### Examples  
  
```csharp  
[C#]  
using (Presentation presentation = new Presentation("demo.ppt"))  
{  
    IOleObjectFrame oleFrame = presentation.Slides[0].Shapes[0] as IOleObjectFrame;  
  
    if (oleFrame != null)  
    {  
        Console.WriteLine("La ruta relativa: " + oleFrame.LinkPathRelative);  
    }   
}  
```  
  
### See Also  
  
* class [OleObjectFrame](../../oleobjectframe)  
* namespace [Aspose.Slides](../../oleobjectframe)  
* assembly [Aspose.Slides](../../../)  
  
<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->