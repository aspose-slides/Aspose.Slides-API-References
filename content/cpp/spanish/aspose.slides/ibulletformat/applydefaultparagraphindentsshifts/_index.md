---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Referencia de API de Aspose.Slides para C++
description: "Establece desplazamientos predeterminados diferentes de cero para el Indent y MarginLeft efectivos del párrafo cuando las viñetas están habilitadas (como hace PowerPoint si se activan viñetas/numeración de párrafo). Si las viñetas están deshabilitadas, simplemente restablece el Indent y MarginLeft del párrafo (como hace PowerPoint si se desactivan viñetas/numeración de párrafo). Los desplazamientos de sangría se aplican respecto al contexto actual de la viñeta: IBulletFormat::get(set)_Type, .NumberedBulletStyle y FontHeight de la primera porción. Los desplazamientos de sangría diferentes de cero se aplican al Indent y MarginLeft efectivos del párrafo actual (haciendo que los valores resultantes sean valores locales)."
type: docs
weight: 235
url: /es/aspose.slides/ibulletformat/applydefaultparagraphindentsshifts/
---
## IBulletFormat::ApplyDefaultParagraphIndentsShifts() método

Establece desplazamientos predeterminados diferentes de cero para el Indent y MarginLeft efectivos del párrafo cuando las viñetas están habilitadas (como hace PowerPoint si se activan viñetas/numeración de párrafo). Si las viñetas están deshabilitadas, simplemente restablece el Indent y MarginLeft del párrafo (como hace PowerPoint si se desactivan viñetas/numeración de párrafo). Los desplazamientos de sangría se aplican con respecto al contexto actual de la viñeta – IBulletFormat::get(set)_Type, .NumberedBulletStyle y FontHeight de la primera porción. Los desplazamientos de sangría no cero se aplican al Indent y MarginLeft efectivos del párrafo actual (haciendo que los valores resultantes sean valores locales).

```cpp
virtual void Aspose::Slides::IBulletFormat::ApplyDefaultParagraphIndentsShifts()=0
```

## Ver también

* Clase [IBulletFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)