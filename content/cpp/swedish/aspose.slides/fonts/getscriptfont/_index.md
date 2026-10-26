---
title: GetScriptFont()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar teckensnittets namn som är associerat med en specifik skripttagg från presentationens tema.
type: docs
weight: 92
url: /sv/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) metod


Hämtar teckensnittets namn som är associerat med en specifik skript-tag från presentationens tema.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47-skriptkoden (t.ex. "Latn", "Cyrl", "Jpan") som används för att identifiera ett skriftsystem. |

## Returvärde

Namnet på teckensnittet som används för det angivna skriptet, eller **null** om skriptet inte är definierat.

## Anmärkningar

Detta exempel visar hur man hämtar teckensnittet som tilldelats det kyrilliska skriptet i presentationens tema. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Se också

* Klass [String](../../../system/string/)
* Klass [Fonts](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)