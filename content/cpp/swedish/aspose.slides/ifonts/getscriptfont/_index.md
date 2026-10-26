---
title: GetScriptFont()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar namnet på teckensnittet som är associerat med en specifik skripttagg i presentationens tema.
type: docs
weight: 92
url: /sv/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) metod

Hämtar namnet på teckensnittet som är associerat med en specifik skripttagg i presentationens tema.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47-skriptkoden (t.ex. "Latn", "Cyrl", "Jpan") som används för att identifiera ett skriftsystem. |

### Returvärde

Namnet på teckensnittet som används för det angivna skriptet, eller **null** om skriptet inte är definierat.

## Anmärkningar

Detta exempel demonstrerar hur man hämtar teckensnittet som är tilldelat det kyrilliska skriptet i presentationens tema. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Se även

* Klass [String](../../../system/string/)
* Klass [IFonts](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)