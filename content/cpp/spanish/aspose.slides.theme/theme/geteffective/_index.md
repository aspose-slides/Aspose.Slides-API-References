---
title: GetEffective()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene los datos de tema efectivos con la herencia aplicada.
type: docs
weight: 53
url: /es/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() método


Obtiene los datos de tema efectivos con la herencia aplicada.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### Valor de retorno

Un [IThemeEffectiveData](../../ithemeeffectivedata/).
## Observaciones



Este ejemplo muestra cómo obtener las propiedades del tema efectivo. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IThemeEffectiveData](../../ithemeeffectivedata/)
* Clase [Theme](../)
* Espacio de nombres [Aspose::Slides::Theme](../../)
* Biblioteca [Aspose.Slides](../../../)