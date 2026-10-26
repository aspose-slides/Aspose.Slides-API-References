---
title: GetSubstitutions()
second_title: Aspose.Slides pro C++ – API Reference
description: Získá informace o písmech, která budou nahrazena při vykreslování prezentace.
type: docs
weight: 66
url: /cs/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() metoda

Získá informace o písmech, která budou nahrazena při vykreslování prezentace.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```

### Návratová hodnota

Kolekce všech náhrad písma [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) metoda

Získá informace o písmech, která budou nahrazena během vykreslování zadaných snímků.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Pole indexů snímků, pro které se mají získat informace o náhradě písma, počínaje 1. |

### Návratová hodnota

Kolekce všech náhrad písma ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) pro zadané snímky.

## Poznámky

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Třída [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Třída [IFontsManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)