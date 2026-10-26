---
title: "System::Drawing::Printing"
second_title: Aspose.Slides pro C++ API referenci
description: 
type: docs
weight: 521
url: /cs/system.drawing.printing/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [Margins](./margins/) | Reprezentuje okraje tištěné stránky. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [PageSettings](./pagesettings/) | Reprezentuje nastavení tištěné stránky. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [PaperSize](./papersize/) | Určuje velikost kusu papíru. |
| [PrintController](./printcontroller/) | Určuje, jak je dokument tištěn při tisku z aplikace [Windows](../system.windows/) Forms. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [PrintDocument](./printdocument/) | Odesílá výstup na tiskárnu, když se tiskne z aplikace [Windows](../system.windows/) Forms. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [PrinterResolution](./printerresolution/) | Reprezentuje rozlišení tiskárny. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [PrinterSettings](./printersettings/) | Reprezentuje nastavení tiskárny. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [PrintEventArgs](./printeventargs/) | Poskytuje data pro události BeginPrint a EndPrint. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [PrintPageEventArgs](./printpageeventargs/) | Poskytuje data pro událost PrintPage. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [QueryPageSettingsEventArgs](./querypagesettingseventargs/) | Poskytuje data pro událost QueryPageSettings. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [StandardPrintController](./standardprintcontroller/) | Určuje tiskový kontrolér, který odesílá informace na tiskárnu. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |

## Výčty

| Výčet | Popis |
| --- | --- |
| [PaperKind](./paperkind/) | Určuje standardní velikosti papíru. |
| [PrintAction](./printaction/) | Určuje typ tiskové operace. |
| [PrintRange](./printrange/) | Určuje, které stránky jsou tištěny. |

## Typedefs

| Typedef | Popis |
| --- | --- |
| [PrintPageEventHandler](./printpageeventhandler/) | Typ funkce, která zpracovává událost PrintPage. |
| [PrintEventHandler](./printeventhandler/) | Typ funkčního objektu, který zpracovává události BeginPrint a EndPrint. |