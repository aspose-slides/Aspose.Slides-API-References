---
title: GetSubstitutions()
second_title: Aspose.Slides for C++ API Referencia
description: Lekérdezi a betűtípusokkal kapcsolatos információkat, amelyeket a prezentáció renderelése során cserélnek ki.
type: docs
weight: 66
url: /hu/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() metódus


Lekérdezi a betűtípusokról szóló információkat, amelyeket a bemutató renderelése során cserélnek ki.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```


### Visszatérési érték

Az összes betűtípus helyettesítés gyűjteménye [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) metódus


Lekérdezi a betűtípusokról szóló információkat, amelyeket a megadott diák renderelése során cserélnek ki.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | A diák indexeinek tömbje, amelyhez a betűtípus helyettesítési információkat le kell kérni, 1-től kezdődően. |

### Visszatérési érték

Az összes betűtípus helyettesítés gyűjteménye ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) a megadott diákra vonatkozóan.
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
* Osztály [IFontsManager](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)