---
title: GetEffective()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene los datos de formato de línea efectivos con la herencia aplicada.
type: docs
weight: 417
url: /es/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() método


Obtiene los datos de formato de línea efectivos con la herencia aplicada.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```


### Valor devuelto

Un [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## Observaciones



Este ejemplo demuestra la obtención de las propiedades de formato de línea efectivos de la forma. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Clase [LineFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)