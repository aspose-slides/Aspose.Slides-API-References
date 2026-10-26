---
title: SetScriptFont()
second_title: Aspose.Slides C++ API-referencia
description: Egy betűkészlet nevet rendel egy adott írásrendszer címkéhez, amely meghatározza, hogyan jelenik meg a szkript szövege a bemutatóban.
type: docs
weight: 105
url: /hu/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) metódus


Egy betűkészlet nevet rendel egy adott írásrendszer címkéjéhez, amely meghatározza, hogyan jelenik meg a szkript szövege a bemutatóban.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | A BCP-47 írásrendszer kódja (például "Arab", "Hebr", "Hans") amely az írásrendszert azonosítja. |
| fontName | [System::String](../../../system/string/) | A betűkészlet neve, amelyet a megadott írásrendszerhez rendelünk. |
## Megjegyzés



Ez a példa bemutatja, hogyan állítható be az arab írásrendszer betűkészlete a "Segoe UI" értékre:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [Fonts](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)