---
title: "System::Diagnostics"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 469
url: /sv/system.diagnostics/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | Tillhandahåller information om filversion. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [PerformanceCounter](./performancecounter/) | Dummy-klass för att översatt kod som använder PerformanceCounter ska kunna kompileras. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [Process](./process/) | Inkapslar processinformation och manipulation. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [ProcessStartInfo](./processstartinfo/) | Beskriver startparametrar för processen. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [StackFrame](./stackframe/) | Hämtar information om en enskild stackram. MSVS only. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [StackTrace](./stacktrace/) | Samling av stackramar. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [Stopwatch](./stopwatch/) | Tillåter tidsmätning. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [TraceListener](./tracelistener/) | Gränssnitt för att reagera på debug- och spårningsinformation. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
## Strukturer

| Struktur | Beskrivning |
| --- | --- |
| [Debug](./debug/) | Samling av debug-metoder som möjliggör att skicka debug-information till registrerade lyssnare. Alla utskriftsfunktioner fungerar endast i [Debug](./debug/). Detta är en statisk typ utan instans-tjänster. Du bör aldrig skapa instanser av den på något sätt. |
| [Debugger](./debugger/) | [Debugger](./debugger/)-gränssnitt. Detta är en statisk typ utan instans-tjänster. Du bör aldrig skapa instanser av den på något sätt. |
| [Trace](./trace/) | Tillhandahåller ett gränssnitt för att komma åt debugger-spårning (om någon finns). Fungerar endast i [Debug](./debug/)-läge. Detta är en statisk typ utan instans-tjänster. Du bör aldrig skapa instanser av den på något sätt. |
## Enum

| Enum | Beskrivning |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | Stil för processfönster. |
| [TraceEventType](./traceeventtype/) | Identifierar typen av händelse som har orsakat spårningen. |
| [TraceLevel](./tracelevel/) | Anger vilka meddelanden som ska skrivas ut för klasserna [System.Diagnostics.Debug](./debug/), [System.Diagnostics.Trace](./trace/) och System.Diagnostics.TraceSwitch. |
## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | Pekartyp. |