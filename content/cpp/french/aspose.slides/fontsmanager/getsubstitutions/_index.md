---
title: GetSubstitutions()
second_title: Référence de l'API C++ Aspose.Slides
description: Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation.
type: docs
weight: 66
url: /fr/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() méthode

Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```

### Valeur de retour

Collection de toutes les substitutions de police [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) méthode

Obtient les informations sur les polices qui seront remplacées lors du rendu des diapositives spécifiées.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Un tableau d'index de diapositives pour lesquelles récupérer les informations de substitution de police, en commençant à 1. |

### Valeur de retour

Une collection de toutes les substitutions de police ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) pour les diapositives spécifiées.

## Remarques

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Classe [FontsManager](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)