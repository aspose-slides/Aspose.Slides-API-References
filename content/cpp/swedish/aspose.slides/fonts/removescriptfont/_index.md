---
title: RemoveScriptFont()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort teckensnittinställningen som är associerad med en specifik skripttagg från temats teckensnittssamling.
type: docs
weight: 118
url: /sv/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) metod

Tar bort teckensnittinställningen som är associerad med en specifik skripttagg från temats teckensnittssamling.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47-skriptkoden vars teckensnittinställning ska tas bort. |
## Anmärkningar

Det här exemplet visar hur man tar bort teckensnittsmappningen för det hebreiska skriptet:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Se även

* Klass [String](../../../system/string/)
* Klass [Fonts](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)