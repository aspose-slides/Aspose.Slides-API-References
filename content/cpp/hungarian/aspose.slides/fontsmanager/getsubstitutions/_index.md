---
title: GetSubstitutions()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a betűtípusokra vonatkozó információkat, amelyek a bemutató renderelése során helyettesítésre kerülnek.
type: docs
weight: 66
url: /hu/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() metódus

Lekéri az információkat a betűtípusokról, amelyek a bemutató renderelése során helyettesítésre kerülnek.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```

### Visszatérési érték

Az összes betűtípushelyettesítés gyűjteménye [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## Megjegyzések

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) metódus

Lekéri az információkat a betűtípusokról, amelyek a megadott diák renderelése során helyettesítésre kerülnek.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | A diaindexek tömbje, amelyekhez a betűtípushelyettesítési információkat kell lekérni, 1-től kezdődően. |

### Visszatérési érték

Az összes betűtípushelyettesítés ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) gyűjteménye a megadott diákra.

## Megjegyzések

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [IEnumerable](../../../system.collections.generic/ienumerable/)
* Osztály [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Osztály [FontsManager](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)