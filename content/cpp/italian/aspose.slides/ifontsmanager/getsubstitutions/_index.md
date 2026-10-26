---
title: GetSubstitutions()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene le informazioni sui caratteri che verranno sostituiti durante il rendering della presentazione.
type: docs
weight: 66
url: /it/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() metodo


Ottiene le informazioni sui caratteri che verranno sostituiti durante il rendering della presentazione.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```


### Valore restituito

Raccolta di tutte le sostituzioni dei caratteri [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Osservazioni




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) metodo


Ottiene le informazioni sui caratteri che verranno sostituiti durante il rendering delle diapositive specificate.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Un array di indici delle diapositive per le quali recuperare le informazioni di sostituzione dei caratteri, a partire da 1. |

### Valore restituito

Una raccolta di tutte le sostituzioni dei caratteri ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) per le diapositive specificate.
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
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Classe [IFontsManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)