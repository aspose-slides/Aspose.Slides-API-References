---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides para Python a través de la API .NET
description: 
type: docs
url: /es/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Establece desplazamientos predeterminados diferentes de cero para el Indent y MarginLeft efectivos del párrafo cuando se habilitan los bullets (como hace PowerPoint si se habilitan los bullets/numación de párrafo). Si los bullets están deshabilitados, solo restablece el Indent y MarginLeft del párrafo (como hace PowerPoint si se deshabilitan los bullets/numación de párrafo). Los desplazamientos de sangrías se aplican según el contexto actual del bullet: IBulletFormat.Type, .NumberedBulletStyle y FontHeight de la primera porción. Los desplazamientos de sangría diferentes de cero se aplican al Indent y MarginLeft efectivos del párrafo actual (haciendo que los valores resultantes sean valores locales).

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Llamar a este método no tiene efecto y lanza **System.InvalidOperationException** en los siguientes casos:<br/>            si el objeto formateado padre no es un párrafo (por ejemplo, llamar a ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() lanzará una excepción);<br/>            o si el párrafo no fue añadido a ninguna colección ITextFrame.Paragraphs (añádalo primero); |

### Ver también
* clase [`BulletFormat`](/slides/python-net/es/aspose.slides/bulletformat)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)