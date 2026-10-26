---
title: GetScriptFont()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Získá název písma přiřazeného ke konkrétnímu štítku skriptu v motivu prezentace.
type: docs
weight: 92
url: /cs/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) metoda

Získá název písma přiřazeného ke konkrétnímu štítku skriptu z motivu prezentace.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kód skriptu BCP-47 (např. "Latn", "Cyrl", "Jpan") používaný k identifikaci psacího systému. |

### Návratová hodnota

Název písma použitého pro zadaný skript, nebo **null**, pokud skript není definován.

## Poznámky

Tento příklad ukazuje, jak získat písmo přiřazené ke cyrilskému skriptu v motivu prezentace.
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [IFonts](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)