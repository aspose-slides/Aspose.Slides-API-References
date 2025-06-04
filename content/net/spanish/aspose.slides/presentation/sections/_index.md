---  
title: Sections
second_title: Referencia de API de Aspose.Slides para .NET  
description: Devuelve una lista de todas las secciones de diapositivas que están definidas en la presentación. Solo lectura ISectionCollectionaspose.slides/isectioncollection.
type: docs  
weight: 220  
url: /es/aspose.slides/presentation/sections/
---  

## Propiedad Presentation.Sections  

Devuelve una lista de todas las secciones de diapositivas que están definidas en la presentación. Solo lectura [`ISectionCollection`](../../isectioncollection).  

```csharp  
public ISectionCollection Sections { get; }  
```  

### Ejemplos  

Los siguientes ejemplos muestran cómo crear Secciones en una Presentación de PowerPoint.  

```csharp  
[C#]  
using (Presentation pres = new Presentation())  
{  
    ISlide defaultSlide = pres.Slides[0];  
    ISlide newSlide1 = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);  
    ISlide newSlide2 = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);  
    ISlide newSlide3 = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);  
    ISlide newSlide4 = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);  
    ISection section1 = pres.Sections.AddSection("Section 1", newSlide1);  
	// section1 terminará en newSlide2 y después comenzará section2  
    ISection section2 = pres.Sections.AddSection("Section 2", newSlide3);  
    pres.Save("pres-sections.pptx", SaveFormat.Pptx);  
    pres.Sections.ReorderSectionWithSlides(section2, 0);  
    pres.Save("pres-sections-moved.pptx", SaveFormat.Pptx);  
    pres.Sections.RemoveSectionWithSlides(section2);  
    pres.Sections.AppendEmptySection("Última sección vacía");  
    pres.Save("pres-section-with-empty.pptx",SaveFormat.Pptx);  
}  
```  

Los siguientes ejemplos muestran cómo cambiar los nombres de las Secciones.  

```csharp  
[C#]  
using (Presentation pres = new Presentation("pres.pptx"))  
{  
   ISection section = pres.Sections[0];  
   section.Name = "Mi sección";  
}  
```  

### Ver También  

* interfaz [ISectionCollection](../../isectioncollection)  
* clase [Presentation](../../presentation)  
* espacio de nombres [Aspose.Slides](../../presentation)  
* ensamblado [Aspose.Slides](../../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->  