---
title: GetEffective()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os dados de tema efetivo com a herança aplicada.
type: docs
weight: 53
url: /pt/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() método


Obtém os dados de tema efetivo com a herança aplicada.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### Valor de Retorno

Um [IThemeEffectiveData](../../ithemeeffectivedata/).
## Observações



Este exemplo demonstra a obtenção de propriedades de tema efetivo. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IThemeEffectiveData](../../ithemeeffectivedata/)
* Classe [Theme](../)
* Espaço de nomes [Aspose::Slides::Theme](../../)
* Biblioteca [Aspose.Slides](../../../)