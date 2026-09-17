---
title: apply_default_paragraph_indents_shifts method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Establece desplazamientos predeterminados diferentes de cero para el Indent y MarginLeft de párrafo efectivos cuando las viñetas están habilitadas (como PowerPoint lo hace si habilita viñetas/numeración de párrafo). Si las viñetas están deshabilitadas, simplemente restablece el Indent y MarginLeft del párrafo (como PowerPoint lo hace si deshabilita viñetas/numeración de párrafo). Los desplazamientos de sangría se aplican con respecto al contexto actual de viñeta - IBulletFormat.Type, .NumberedBulletStyle y FontHeight de la primera porción. Los desplazamientos de sangría diferentes de cero se aplican al Indent y MarginLeft efectivos del párrafo actual (haciendo que los valores resultantes sean valores locales).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Llamar a este método no importa y lanza **System.InvalidOperationException** en los siguientes casos:<br/>            si el objeto formateado padre no es un párrafo (por ejemplo al llamar a ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() se lanzará una excepción);<br/>            o si el párrafo no se agregó a ninguna colección ITextFrame.Paragraphs (agregue primero); |



### Ver también
* clase [`IBulletFormat`](/slides/python-net/es/aspose.slides/ibulletformat)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)