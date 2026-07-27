---
title: GetEffective()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene los datos de fondo efectivos con la herencia aplicada.
type: docs
weight: 118
url: /es/aspose.slides/background/geteffective/
---
## Background::GetEffective() método


Obtiene los datos de fondo efectivos con la herencia aplicada.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### Valor de retorno

Un [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## Observaciones



Este ejemplo muestra cómo obtener propiedades de fondo efectivas. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Class [Background](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)