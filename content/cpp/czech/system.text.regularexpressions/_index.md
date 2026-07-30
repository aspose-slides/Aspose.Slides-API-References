---
title: "System::Text::RegularExpressions"
second_title: Aspose.Slides pro C++ – referenční příručka API
description: 
type: docs
weight: 989
url: /cs/system.text.regularexpressions/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [Capture](./capture/) | Výsledek shody jednoho podvýrazu. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [CaptureCollection](./capturecollection/) | Seznam zachycení provedených jednou zachytávací skupinou. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [Group](./group/) | Výsledek shody provedené jednou zachytávací skupinou. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [GroupCollection](./groupcollection/) | Seznam zachytávacích skupin v jedné shodě. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) ukazatel sbírky. Tento typ je ukazatel pro správu odstraňování jiných objektů. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo jako const reference. |
| [Match](./match/) | [Single](../system/single/) shoda regulárního výrazu nad řetězcem. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [MatchCollection](./matchcollection/) | Sbírka shod provedených opakovaným aplikováním regulárního výrazu na řetězec. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [Regex](./regex/) | Regulární výraz, který používá syntaxi podobnou C#. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
## Funkce

| Funkce | Popis |
| --- | --- |
|  [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | Obal pro udržení třídy MatchHolder bez jejího zahrnutí spolu s PCRE2. |
## Výčty

| Výčet | Popis |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) možnosti. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [UStringPtr](./ustringptr/) | Sdílený UnicodeString pro zamezení kopírování. |
| [CapturePtr](./captureptr/) | Ukazatel na objekt jedné zachytávací položky. |
| [CaptureCollectionPtr](./capturecollectionptr/) | Ukazatel na sbírku zachycení. |
| [GroupPtr](./groupptr/) | Ukazatel na skupinu. |
| [RegexPtr](./regexptr/) | [Regex](./regex/) ukazatel. |
| [MatchPtr](./matchptr/) | [Match](./match/) ukazatel. |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) ukazatel sbírky. |
| [MatchEvaluator](./matchevaluator/) | Typ delegáta pro vyhodnocení shody. |