---
title: SetScriptFont()
second_title: Aspose.Slides pro C++ API Reference
description: Přiřadí název písma k určitému tagu skriptu, který určuje, jak bude text tohoto skriptu vykreslen v prezentaci.
type: docs
weight: 105
url: /cs/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) metoda

Přiřadí název písma ke konkrétnímu tagu skriptu, který určuje, jak bude text tohoto skriptu vykreslen v prezentaci.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kód písma BCP-47 (např. "Arab", "Hebr", "Hans") identifikující systém zápisu. |
| fontName | [System::String](../../../system/string/) | Název písma, které se má přiřadit ke specifikovanému skriptu. |

## Poznámky

Tento příklad ukazuje, jak nastavit písmo pro arabský skript na "Segoe UI":
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [Fonts](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)