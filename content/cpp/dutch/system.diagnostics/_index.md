---
title: "System::Diagnostics"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 469
url: /nl/system.diagnostics/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | Biedt informatie over de bestandsversie. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik die pointer om deze aan functies als argument door te geven. |
| [PerformanceCounter](./performancecounter/) | Dummy-klasse om vertaalde code die PerformanceCounter gebruikt te compileren. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik die pointer om deze aan functies als argument door te geven. |
| [Process](./process/) | Omvat procesinformatie en -manipulatie. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik die pointer om deze aan functies als argument door te geven. |
| [ProcessStartInfo](./processstartinfo/) | Beschrijft startparameters van een proces. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik die pointer om deze aan functies als argument door te geven. |
| [StackFrame](./stackframe/) | Haalt informatie op over één stack-frame. Alleen MSVS. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik die pointer om deze aan functies als argument door te geven. |
| [StackTrace](./stacktrace/) | Collectie van stack-frames. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik die pointer om deze aan functies als argument door te geven. |
| [Stopwatch](./stopwatch/) | Staat tijdmeting toe. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik die pointer om deze aan functies als argument door te geven. |
| [TraceListener](./tracelistener/) | Interface om te reageren op debug- en trace-informatie. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik die pointer om deze aan functies als argument door te geven. |

## Structuren

| Struct | Beschrijving |
| --- | --- |
| [Debug](./debug/) | Collectie van debug-methoden die het mogelijk maken debug-informatie naar geregistreerde listeners te sturen. Alle uitvoerfuncties werken alleen in [Debug](./debug/). Dit is een statisch type zonder instantie-services. Je mag nooit op welke manier dan ook instanties ervan creëren. |
| [Debugger](./debugger/) | [Debugger](./debugger/) interface. Dit is een statisch type zonder instantie-services. Je mag nooit op welke manier dan ook instanties ervan creëren. |
| [Trace](./trace/) | Biedt een interface om debugger-trace (indien aanwezig) te benaderen. Werkt alleen in [Debug](./debug/)-modus. Dit is een statisch type zonder instantie-services. Je mag nooit op welke manier dan ook instanties ervan creëren. |

## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | Stijl van het procesvenster. |
| [TraceEventType](./traceeventtype/) | Identificeert het type gebeurtenis dat de trace heeft veroorzaakt. |
| [TraceLevel](./tracelevel/) | Specificeert welke berichten moeten worden uitgegeven voor de [System.Diagnostics.Debug](./debug/), [System.Diagnostics.Trace](./trace/) en System.Diagnostics.TraceSwitch klassen. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | Pointer-type. |