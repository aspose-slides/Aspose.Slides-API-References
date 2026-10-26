---
title: GetSubstitutions()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation.
type: docs
weight: 66
url: /fr/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() méthode

Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```

### Valeur de retour

Collection de toutes les substitutions de polices [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) méthode

Obtient les informations sur les polices qui seront remplacées lors du rendu des diapositives spécifiées.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Un tableau d'indices de diapositives pour lesquelles récupérer les informations de substitution de police, à partir de 1. |

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
* Classe [IFontsManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)