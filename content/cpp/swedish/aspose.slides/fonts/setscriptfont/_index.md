---
title: SetScriptFont()
second_title: Aspose.Slides för C++ API-referens
description: Tilldelar ett typsnittsnamn till en specifik skripttagg, vilket definierar hur text i det skriptet kommer att renderas i presentationen.
type: docs
weight: 105
url: /sv/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) metod


Tilldelar ett typsnittsnamn till en specifik skripttagg, vilket definierar hur text i det skriptet kommer att renderas i presentationen.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47-skriptkoden (t.ex. "Arab", "Hebr", "Hans") som identifierar skriftsystemet. |
| fontName | [System::String](../../../system/string/) | Namnet på typsnittet som ska tilldelas det angivna skriptet. |
## Anmärkningar



Detta exempel visar hur man ställer in typsnittet för det arabiska skriptet till "Segoe UI": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Se även

* Klass [String](../../../system/string/)
* Klass [Fonts](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)