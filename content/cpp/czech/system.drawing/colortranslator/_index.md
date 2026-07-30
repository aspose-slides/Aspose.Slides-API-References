---
title: ColorTranslator
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: "Provádí překlady barev. Objektům této třídy by měla být alokována pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k běhovým chybám a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 66
url: /cs/system.drawing/colortranslator/
---
## ColorTranslator třída

Performs color translations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) funkce. Never create instance of this type on stack or using operator new, as it will result in běhové chyby and/or chyby tvrzení. Always wrap this class into [System::SmartPtr](../../system/smartptr/) ukazatel and use this pointer to pass it to functions as argument.

```cpp
class ColorTranslator
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Převádí zadanou reprezentaci barvy HTML na ekvivalentní objekt [Color](../color/). |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Převádí zadanou barvu [Windows](../../system.windows/) na ekvivalentní objekt [Color](../color/). |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Převádí zadaný objekt [Color](../color/) na řetězcovou reprezentaci ekvivalentní barvy HTML. |

## Viz také

* Jmenný prostor [System::Drawing](../)
* Knihovna [Aspose.Slides](../../)