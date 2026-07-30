---
title: GetSubstitutions()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera le informazioni sui caratteri che saranno sostituiti durante il rendering della presentazione.
type: docs
weight: 66
url: /it/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() metodo

Recupera le informazioni sui caratteri che saranno sostituiti durante il rendering della presentazione.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```

### Valore di ritorno

Collezione di tutte le sostituzioni di caratteri [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) metodo

Recupera le informazioni sui caratteri che saranno sostituiti durante il rendering delle diapositive specificate.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Un array di indici delle diapositive per le quali recuperare le informazioni di sostituzione dei caratteri, a partire da 1. |

### Valore di ritorno

Una collezione di tutte le sostituzioni di caratteri ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) per le diapositive specificate.

## Osservazioni

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)