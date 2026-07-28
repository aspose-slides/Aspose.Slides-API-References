---
title: GetScriptFont()
second_title: Aspose.Slides for C++ API Referencia
description: Lekéri a betűtípus nevét, amely egy adott írásjelcímkéhez kapcsolódik a bemutató témájában.
type: docs
weight: 92
url: /hu/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) metódus


Lekéri a betűtípus nevét, amely egy adott írásjelcímkéhez tartozik a bemutató témájában.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | A BCP-47 írásjel kód (pl. "Latn", "Cyrl", "Jpan"), amely egy írásrendszert azonosít. |

### Visszatérési érték

A megadott írásjelhez használt betűtípus neve, vagy **null**, ha az írásjel nincs definiálva.

## Megjegyzések



Ez a példa bemutatja, hogyan lehet lekérni a cirill írásjelhez rendelt betűtípust a bemutató témájában. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [Fonts](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)