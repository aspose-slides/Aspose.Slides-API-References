---
title: GetScriptFont()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Pobiera nazwę czcionki powiązaną z określonym tagiem skryptu z motywu prezentacji.
type: docs
weight: 92
url: /pl/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) metoda

Pobiera nazwę czcionki powiązaną z określonym tagiem skryptu z motywu prezentacji.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kod skryptu BCP-47 (np. "Latn", "Cyrl", "Jpan") używany do identyfikacji systemu pisma. |

### Wartość zwracana

Nazwa czcionki używanej dla określonego skryptu lub **null**, jeśli skrypt nie jest zdefiniowany.

## Uwagi

Ten przykład pokazuje, jak pobrać czcionkę przypisaną do skryptu cyrylicy w motywie prezentacji.
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Zobacz również

* Klasa [String](../../../system/string/)
* Klasa [IFonts](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)