---
title: RemoveScriptFont()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraňuje nastavení písma spojené s konkrétním tagem skriptu ze sbírky písem motivu.
type: docs
weight: 118
url: /cs/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) metoda

Odstraňuje nastavení písma spojené s konkrétním tagem skriptu ze sbírky písem motivu.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kód BCP-47 skriptu, jehož nastavení písma by mělo být odstraněno. |
## Poznámky

Tento příklad ukazuje, jak odstranit mapování písma pro hebrejský skript: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [Fonts](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)