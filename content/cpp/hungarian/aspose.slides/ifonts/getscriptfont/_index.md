---
title: GetScriptFont()
second_title: Aspose.Slides for C++ API-referencia
description: Lekéri a betűtípus nevét, amely egy adott script címkéhez van rendelve a prezentáció témájában.
type: docs
weight: 92
url: /hu/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) metódus

Lekéri a betűtípus nevét, amely egy adott script címkéhez van rendelve a prezentáció témájában.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | A BCP-47 script kód (például "Latn", "Cyrl", "Jpan"), amely egy írásrendszert azonosít. |

### Visszatérési érték

A megadott scripthez használt betűtípus neve, vagy **null**, ha a script nincs definiálva.

## Megjegyzések

Ez a példa bemutatja, hogyan lehet lekérdezni a cirill írásrendszerhez rendelt betűtípust a prezentáció témájában. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IFonts](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)