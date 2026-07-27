---
title: InsertClone()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inserta una copia de una diapositiva maestra especificada en la posición especificada de la colección. Las diapositivas de diseño vinculadas también se copiarán.
type: docs
weight: 105
url: /es/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) method


Inserta una copia de una diapositiva maestra especificada en la posición especificada de la colección. Las diapositivas de diseño vinculadas también se copiarán.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice de la nueva diapositiva. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) para clonar. |

### Valor devuelto

Diapositiva maestra insertada.
## Observaciones



El siguiente ejemplo muestra cómo clonar una diapositiva maestra en otro PowerPoint [Presentation](../../presentation/). 
```cpp
// Instanciar la clase Presentation para cargar el archivo de presentación de origen
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Instanciar la clase Presentation para la presentación de destino (donde se clonará la diapositiva)
auto destPres = System::MakeObject<Presentation>();

// Instanciar ISlide a partir de la colección de diapositivas en la presentación de origen junto con
// Diapositiva maestra
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Obtener las diapositivas maestras de la presentación de destino
auto masters = destPres->get_Masters();
// Clonar la diapositiva maestra deseada de la presentación de origen a la colección de maestras en la
// Presentación de destino
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Colección de diapositivas en la presentación de destino
auto slides = destPres->get_Slides();
// Clonar la diapositiva de origen a la colección de diapositivas de destino.
slides->AddClone(sourceSlide, iSlide, true);
// Guardar la presentación de destino en disco
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMasterSlide](../../imasterslide/)
* Clase [MasterSlideCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)