---
title: Equals()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina si las dos instancias de IBaseSlide son iguales. El valor devuelto se calcula en función de la estructura de la diapositiva y el contenido estático. Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, p. ej. SlideId y el contenido dinámico, p. ej. el valor de la fecha actual en el marcador de posición Date.
type: docs
weight: 170
url: /es/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) método


Determina si las dos [IBaseSlide](../../ibaseslide/) instancias son iguales. El valor devuelto se calcula en función de la estructura de la diapositiva y el contenido estático. Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, p. ej. SlideId y el contenido dinámico, p. ej. el valor de la fecha actual en Date [Placeholder](../../placeholder/).

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | El [IBaseSlide](../../ibaseslide/) para comparar con el [IBaseSlide](../../ibaseslide/) actual. |

### Valor de retorno

**true** si el [IBaseSlide](../../ibaseslide/) especificado es igual al [IBaseSlide](../../ibaseslide/) actual; de lo contrario, **false**.
## Observaciones



El siguiente ejemplo muestra cómo comparar dos diapositivas. 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IBaseSlide](../../ibaseslide/)
* Clase [BaseSlide](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)