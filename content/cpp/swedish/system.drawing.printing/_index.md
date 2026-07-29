---
title: "System::Drawing::Printing"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 521
url: /sv/system.drawing.printing/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Margins](./margins/) | Representerar marginaler på en utskriven sida. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [PageSettings](./pagesettings/) | Representerar inställningar för en utskriven sida. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [PaperSize](./papersize/) | Anger storleken på ett papper. |
| [PrintController](./printcontroller/) | Styr hur ett dokument skrivs ut när du skriver ut från en [Windows](../system.windows/) Forms-applikation. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [PrintDocument](./printdocument/) | Skickar utdata till en skrivare när du skriver ut från en [Windows](../system.windows/) Forms-applikation. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [PrinterResolution](./printerresolution/) | Representerar en upplösning för en skrivare. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [PrinterSettings](./printersettings/) | Representerar inställningar för en skrivare. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [PrintEventArgs](./printeventargs/) | Tillhandahåller data för händelserna BeginPrint och EndPrint. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [PrintPageEventArgs](./printpageeventargs/) | Tillhandahåller data för PrintPage-händelsen. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [QueryPageSettingsEventArgs](./querypagesettingseventargs/) | Tillhandahåller data för händelsen QueryPageSettings. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [StandardPrintController](./standardprintcontroller/) | Anger en utskriftskontroller som skickar information till en skrivare. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
## Uppräkningar

| Enumeration | Beskrivning |
| --- | --- |
| [PaperKind](./paperkind/) | Anger standardpappersstorlekar. |
| [PrintAction](./printaction/) | Anger en typ av utskriftsoperation. |
| [PrintRange](./printrange/) | Anger vilka sidor som skrivs ut. |
## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [PrintPageEventHandler](./printpageeventhandler/) | En typ av funktion som hanterar PrintPage-händelsen. |
| [PrintEventHandler](./printeventhandler/) | En typ av funktionsobjekt som hanterar händelserna BeginPrint och EndPrint. |