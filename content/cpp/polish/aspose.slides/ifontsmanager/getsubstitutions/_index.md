---
title: GetSubstitutions()
second_title: Aspose.Slides dla C++ Referencja API
description: Pobiera informacje o czcionkach, które zostaną zastąpione podczas renderowania prezentacji.
type: docs
weight: 66
url: /pl/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() metoda


Pobiera informacje o czcionkach, które zostaną zastąpione podczas renderowania prezentacji.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```


### Wartość zwracana

Kolekcja wszystkich zamian czcionek [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Uwagi




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) metoda


Pobiera informacje o czcionkach, które zostaną zastąpione podczas renderowania określonych slajdów.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tablica indeksów slajdów, dla których należy pobrać informacje o zamianie czcionek, zaczynając od 1. |

### Wartość zwracana

Kolekcja wszystkich zamian czcionek ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) dla określonych slajdów.
## Uwagi




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)