---
title: equals method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/baseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Determina si las dos instancias de IBaseSlide son iguales.
El valor devuelto se calcula en función de la estructura y el contenido estático de la diapositiva.
Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, p. ej. SlideId y el contenido dinámico, p. ej. el valor de la fecha actual en Date Placeholder.

### Devuelve

**true** si el IBaseSlide especificado es igual al IBaseSlide actual; de lo contrario, **false** .

```python
def equals(self, slide):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide) | El IBaseSlide para comparar con el IBaseSlide actual. |

### Ver también
* clase [`BaseSlide`](/slides/python-net/es/aspose.slides/baseslide)
* clase [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)