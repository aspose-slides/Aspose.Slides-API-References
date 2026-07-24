---
title: GetSubstitutions()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft die Informationen über Schriftarten ab, die bei der Darstellung der Präsentation ersetzt werden.
type: docs
weight: 66
url: /de/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() Methode

Ruft die Informationen über Schriftarten ab, die bei der Darstellung der Präsentation ersetzt werden.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```

### Rückgabewert

Sammlung aller Schriftart-Ersetzungen [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## Bemerkungen

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) Methode

Ruft die Informationen über Schriftarten ab, die bei der Darstellung der angegebenen Folien ersetzt werden.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Ein Array von Folienindizes, für die Schriftart-Ersetzungsinformationen abgerufen werden sollen, beginnend bei 1. |

### Rückgabewert

Eine Sammlung aller Schriftart-Ersetzungen ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) für die angegebenen Folien.

## Bemerkungen

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Klasse [IFontsManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)