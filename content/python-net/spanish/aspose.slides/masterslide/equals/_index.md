---
title: equals method
second_title: Aspose.Slides para Python a través de la API .NET
description: 
type: docs
url: /es/aspose.slides/masterslide/equals/
weight: 30
---
## equals(self, slide) {#ibaseslide}
Determina si las dos instancias de IBaseSlide son iguales.
            El valor devuelto se calcula en función de la estructura de la diapositiva y el contenido estático.
            Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, p. ej., SlideId, ni el contenido dinámico, p. ej., el valor de fecha actual en el marcador de posición de fecha.

### Devuelve

**true**  if the specified IBaseSlide is equal to the current IBaseSlide; 
            otherwise, **false** .


```python
def equals(self, slide):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide) | The IBaseSlide to compare with the current IBaseSlide. |


### Ver también
* clase [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide)
* clase [`MasterSlide`](/slides/python-net/es/aspose.slides/masterslide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)