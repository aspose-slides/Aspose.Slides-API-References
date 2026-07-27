---
title: GetSubstitutions()
second_title: Referência da API Aspose.Slides para C++
description: Obtém as informações sobre as fontes que serão substituídas na renderização da apresentação.
type: docs
weight: 66
url: /pt/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() método

Obtém as informações sobre as fontes que serão substituídas na renderização da apresentação.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```

### Valor de Retorno

Coleção de todas as substituições de fontes [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## Observações

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) método

Obtém as informações sobre as fontes que serão substituídas durante a renderização dos slides especificados.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Um array de índices de slides para os quais recuperar as informações de substituição de fontes, começando em 1. |

### Valor de Retorno

Uma coleção de todas as substituições de fontes ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) para os slides especificados.

## Observações

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Classe [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)