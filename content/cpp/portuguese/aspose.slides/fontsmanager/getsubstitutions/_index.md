---
title: GetSubstitutions()
second_title: Referência da API Aspose.Slides para C++
description: Obtém as informações sobre fontes que serão substituídas na renderização da apresentação.
type: docs
weight: 66
url: /pt/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() method


Obtém as informações sobre fontes que serão substituídas na renderização da apresentação.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
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




## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) method


Obtém as informações sobre fontes que serão substituídas durante a renderização dos slides especificados.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Um array de índices de slides para os quais recuperar as informações de substituição de fontes, iniciando em 1. |

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

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Classe [FontsManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)