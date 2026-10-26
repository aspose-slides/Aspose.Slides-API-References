---
title: FileVersionInfo
second_title: Aspose.Slides pro C++ - referenční API
description: "Poskytuje informace o verzi souboru. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání funkci jako argument."
type: docs
weight: 1
url: /cs/system.diagnostics/fileversioninfo/
---
## FileVersionInfo třída

Poskytuje informace o verzi souboru. Objekty této třídy by měly být alokovány pouze pomocí [System::MakeObject()](../../system/makeobject/) funkce. Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do [System::SmartPtr](../../system/smartptr/) ukazatele a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class FileVersionInfo
```

## Metody

| Method | Description |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | Získá pole verze produktu. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | Získá informace o verzi souboru; není implementováno. |

## Viz také

* Jmenný prostor [System::Diagnostics](../)
* Knihovna [Aspose.Slides](../../)