---
title: GetSubstitutions()
second_title: Aspose.Slides für C++ API Referenz
description: Ruft die Informationen zu Schriften ab, die bei der Darstellung der Präsentation ersetzt werden.
type: docs
weight: 66
url: /de/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() Methode

Ruft die Informationen zu Schriften ab, die bei der Darstellung der Präsentation ersetzt werden.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```

### Rückgabewert

Sammlung aller Schriftarten-Ersetzungen [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## Bemerkungen

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) Methode

Ruft die Informationen zu Schriften ab, die bei der Darstellung der angegebenen Folien ersetzt werden.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Ein Array von Folienindizes, für die Schriftarten-Ersetzungsinformationen abgerufen werden sollen, beginnend bei 1. |

### Rückgabewert

Eine Sammlung aller Schriftarten-Ersetzungen ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) für die angegebenen Folien.

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
* Klasse [FontsManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)