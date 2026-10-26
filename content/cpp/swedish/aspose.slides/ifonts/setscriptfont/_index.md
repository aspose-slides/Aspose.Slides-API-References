---
title: SetScriptFont()
second_title: Aspose.Slides för C++ API-referens
description: Tilldelar ett teckensnittsnamn till en specifik skripttagg, som definierar hur texten för det skriptet kommer att renderas i presentationen.
type: docs
weight: 105
url: /sv/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) metod


Tilldelar ett teckensnittsnamn till en specifik skript-tag, som definierar hur texten för det skriptet ska renderas i presentationen.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47-skriptkoden (t.ex. "Arab", "Hebr", "Hans") som identifierar skriftsystemet. |
| fontName | [System::String](../../../system/string/) | Namnet på teckensnittet som ska tilldelas det angivna skriptet. |
## Anmärkningar



Det här exemplet visar hur man ställer in teckensnittet för det arabiska skriptet till "Segoe UI": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Se också

* Klass [String](../../../system/string/)
* Klass [IFonts](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)