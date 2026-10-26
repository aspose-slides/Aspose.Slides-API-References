---
title: SetScriptFont()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Przypisuje nazwę czcionki do określonego tagu skryptu, który definiuje sposób renderowania tekstu tego skryptu w prezentacji.
type: docs
weight: 105
url: /pl/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) metoda

Przypisuje nazwę czcionki do określonego tagu skryptu, który definiuje sposób renderowania tekstu tego skryptu w prezentacji.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kod skryptu BCP-47 (np. "Arab", "Hebr", "Hans") określający system pisma. |
| fontName | [System::String](../../../system/string/) | Nazwa czcionki, która ma zostać przypisana do określonego skryptu. |
## Uwagi

Ten przykład pokazuje, jak ustawić czcionkę dla skryptu arabskiego na "Segoe UI":
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Zobacz również

* Klasa [String](../../../system/string/)
* Klasa [Fonts](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)