---
title: SetScriptFont()
second_title: Aspose.Slides pro C++ referenci API
description: Přiřadí název písma konkrétní značce skriptu, která určuje, jak bude text tohoto skriptu v prezentaci zobrazen.
type: docs
weight: 105
url: /cs/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) metoda


Přiřadí název písma konkrétní značce skriptu, která určuje, jak bude text tohoto skriptu v prezentaci vykreslen.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kód skriptu BCP-47 (např. \"Arab\", \"Hebr\", \"Hans\") identifikující systém zápisu. |
| fontName | [System::String](../../../system/string/) | Název písma, které se má přiřadit k určenému skriptu. |
## Poznámky



Tento příklad ukazuje, jak nastavit písmo pro arabský skript na \"Segoe UI\": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [IFonts](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)