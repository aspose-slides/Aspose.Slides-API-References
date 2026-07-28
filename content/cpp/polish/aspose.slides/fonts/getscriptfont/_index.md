---
title: GetScriptFont()
second_title: Aspose.Slides dla C++ – Odniesienie API
description: Pobiera nazwę czcionki powiązaną z określoną etykietą skryptu z motywu prezentacji.
type: docs
weight: 92
url: /pl/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) metoda


Pobiera nazwę czcionki powiązaną z określoną etykietą skryptu z motywu prezentacji.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kod skryptu BCP-47 (np. "Latn", "Cyrl", "Jpan") używany do identyfikacji systemu pisania. |

### Wartość zwracana

Nazwa czcionki używanej dla określonego skryptu lub **null**, jeśli skrypt nie jest zdefiniowany.
## Uwagi



Ten przykład pokazuje, jak pobrać czcionkę przypisaną do skryptu cyrylica w motywie prezentacji. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [Fonts](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)