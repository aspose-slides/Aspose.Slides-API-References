---
title: get_Sections()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve una lista de todas las secciones de diapositivas que están definidas en la presentación. Solo lectura ISectionCollection.
type: docs
weight: 66
url: /es/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() método


Devuelve una lista de todas las secciones de diapositivas que están definidas en la presentación. Solo lectura [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## Comentarios


Los siguientes ejemplos muestran cómo crear Secciones en un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 se terminará en newSlide2 y después de ella comenzará section2
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 Los siguientes ejemplos muestran cómo cambiar los nombres de las Secciones. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISectionCollection](../../isectioncollection/)
* Clase [Presentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)