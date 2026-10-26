---
title: equals method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/ibaseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Determina si las dos instancias de IBaseSlide son iguales.
            El valor devuelto se calcula en función de la estructura de la diapositiva y su contenido estático.
            Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, e.g. SlideId y el contenido dinámico, e.g. el valor de fecha actual en el Marcador de posición de fecha.

### Devuelve

**true**  si el IBaseSlide especificado es igual al IBaseSlide actual; 
            de lo contrario, **false** .

```python
def equals(self, slide):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide) | El IBaseSlide para comparar con el IBaseSlide actual. |

### Ver también
* clase [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)