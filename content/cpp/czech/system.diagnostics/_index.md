---
title: "System::Diagnostics"
second_title: Aspose.Slides pro C++ – reference API
description: 
type: docs
weight: 469
url: /cs/system.diagnostics/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | Poskytuje informace o verzi souboru. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [PerformanceCounter](./performancecounter/) | Fiktivní třída pro překlad kódu používajícího PerformanceCounter, aby se mohl zkompilovat. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [Process](./process/) | Zapouzdřuje informace o procesu a jejich manipulaci. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [ProcessStartInfo](./processstartinfo/) | Popisuje parametry spuštění procesu. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [StackFrame](./stackframe/) | Získává informace o jedné zásobníkové rámci. Pouze MSVS. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [StackTrace](./stacktrace/) | Sbírka zásobníkových rámců. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [Stopwatch](./stopwatch/) | Umožňuje měření času. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [TraceListener](./tracelistener/) | Rozhraní pro reakci na ladicí a trasovací informace. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
## Struktury

| Struktura | Popis |
| --- | --- |
| [Debug](./debug/) | Sbírka ladicích metod umožňujících odesílání ladicích informací registrovaným posluchačům. Všechny výstupní funkce fungují pouze v [Debug](./debug/). Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance žádným způsobem. |
| [Debugger](./debugger/) | [Debugger](./debugger/) rozhraní. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance žádným způsobem. |
| [Trace](./trace/) | Poskytuje rozhraní pro přístup k ladicímu trasování (pokud existuje). Funguje pouze v režimu [Debug](./debug/). Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance žádným způsobem. |
## Výčty

| Výčet | Popis |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | Styl okna procesu. |
| [TraceEventType](./traceeventtype/) | Identifikuje typ události, která způsobila trasování. |
| [TraceLevel](./tracelevel/) | Určuje, jaké zprávy se mají vypisovat pro třídy [System.Diagnostics.Debug](./debug/), [System.Diagnostics.Trace](./trace/) a System.Diagnostics.TraceSwitch. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | Typ ukazatele. |