---
title: RemoveScriptFont()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Usuwa ustawienie czcionki powiązane z określonym znacznikiem skryptu w kolekcji czcionek motywu.
type: docs
weight: 118
url: /pl/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) metoda

Usuwa ustawienie czcionki powiązane z określonym znacznikiem skryptu z kolekcji czcionek motywu.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kod skryptu BCP-47, którego ustawienie czcionki należy usunąć. |

## Uwagi

Ten przykład pokazuje, jak usunąć mapowanie czcionki dla skryptu hebrajskiego: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IFonts](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)