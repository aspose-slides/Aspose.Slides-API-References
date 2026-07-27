---
title: GetFontName()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o nome da fonte, substituindo a referência ao tema por uma fonte real utilizada.
type: docs
weight: 27
url: /pt/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) method


Retorna o nome da fonte, substituindo a referência ao tema por uma fonte real usada.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) da qual o nome da fonte temático deve ser obtido. Cabe ao chamador fornecer um valor correto. Veja [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### Valor de retorno

Nome da fonte.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* Classe [FontData](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)