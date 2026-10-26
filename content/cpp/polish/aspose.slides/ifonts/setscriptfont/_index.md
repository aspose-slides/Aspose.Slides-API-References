---
title: SetScriptFont()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Przypisuje nazwę czcionki do określonego znacznika skryptu, co definiuje sposób renderowania tekstu tego skryptu w prezentacji.
type: docs
weight: 105
url: /pl/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) method

Przypisuje nazwę czcionki do określonego znacznika skryptu, co definiuje sposób renderowania tekstu tego skryptu w prezentacji.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kod skryptu BCP-47 (np. "Arab", "Hebr", "Hans") identyfikujący system pisma. |
| fontName | [System::String](../../../system/string/) | Nazwa czcionki, którą należy przypisać do określonego skryptu. |

## Uwagi

Ten przykład pokazuje, jak ustawić czcionkę dla skryptu arabskiego na "Segoe UI":
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IFonts](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)