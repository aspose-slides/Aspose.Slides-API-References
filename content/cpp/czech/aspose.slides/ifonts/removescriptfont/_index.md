---
title: RemoveScriptFont()
second_title: Aspose.Slides pro C++ – reference API
description: Odstraňuje nastavení písma spojené s konkrétní značkou skriptu z kolekce písem motivu.
type: docs
weight: 118
url: /cs/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) method


Odstraňuje nastavení písma spojené se specifickým značkou skriptu z kolekce písem motivu.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kód skriptu BCP-47, jehož nastavení písma by mělo být odstraněno. |
## Poznámky



Tento příklad ukazuje, jak odstranit mapování písma pro hebrejský skript: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [IFonts](../)
* Obor názvů [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)