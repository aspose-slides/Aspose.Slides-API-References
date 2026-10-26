---
title: SetScriptFont()
second_title: Aspose.Slides C++ API referenciája
description: Betűkészlet nevet rendel egy adott script címkéhez, amely meghatározza, hogyan jelenik meg a script szövege a prezentációban.
type: docs
weight: 105
url: /hu/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) metódus


Betűkészlet nevet rendel egy adott script címkéhez, amely meghatározza, hogyan lesz a script szövege megjelenítve a prezentációban.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | A BCP-47 script kód (például \"Arab\", \"Hebr\", \"Hans\"), amely az írásrendszert azonosít. |
| fontName | [System::String](../../../system/string/) | A betűkészlet neve, amelyet a megadott scripthez kell hozzárendelni. |
## Megjegyzés



Ez a példa bemutatja, hogyan állítható be a betűkészlet az arab scripthez \"Segoe UI\"-ra: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IFonts](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)