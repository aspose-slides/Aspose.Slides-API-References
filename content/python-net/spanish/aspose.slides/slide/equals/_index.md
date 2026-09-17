---
title: equals method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/slide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Determina si las dos instancias de IBaseSlide son iguales.
            El valor devuelto se calcula en función de la estructura de la diapositiva y su contenido estático.
            Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, por ejemplo SlideId, ni el contenido dinámico, por ejemplo el valor de la fecha actual en el Marcador de fecha.

### Devuelve

**true**  si el IBaseSlide especificado es igual al IBaseSlide actual; 
            de lo contrario, **false** .

```python
def equals(self, slide):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide) | El IBaseSlide a comparar con el IBaseSlide actual. |

### Ver también
* clase [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide)
* clase [`Slide`](/slides/python-net/es/aspose.slides/slide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)