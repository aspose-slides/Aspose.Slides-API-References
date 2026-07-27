---
title: Equals()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina si las dos instancias IBaseSlide son iguales. El valor devuelto se calcula en función de la estructura de la diapositiva y su contenido estático. Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, p. ej., SlideId, ni el contenido dinámico, p. ej., el valor de la fecha actual en Marcador de posición de fecha.
type: docs
weight: 183
url: /es/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) método

Determina si las dos instancias [IBaseSlide](../) son iguales. El valor devuelto se calcula en función de la estructura de la diapositiva y su contenido estático. Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, p. ej., SlideId y contenido dinámico, p. ej., el valor de la fecha actual en Fecha [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | El [IBaseSlide](../) para comparar con el [IBaseSlide](../) actual. |

### Valor devuelto

**true** si el [IBaseSlide](../) especificado es igual al [IBaseSlide](../) actual; de lo contrario, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IBaseSlide](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)