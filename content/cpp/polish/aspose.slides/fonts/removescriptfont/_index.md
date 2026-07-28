---
title: RemoveScriptFont()
second_title: Referencja API Aspose.Slides dla C++
description: Usuwa ustawienie czcionki związane z określoną etykietą skryptu w kolekcji czcionek motywu.
type: docs
weight: 118
url: /pl/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) metoda


Usuwa ustawienie czcionki powiązane z określoną etykietą skryptu w kolekcji czcionek motywu.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kod skryptu BCP-47, którego ustawienie czcionki powinno zostać usunięte. |
## Uwagi



Ten przykład pokazuje, jak usunąć mapowanie czcionki dla skryptu hebrajskiego: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Zobacz również

* Klasa [String](../../../system/string/)
* Klasa [Fonts](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)