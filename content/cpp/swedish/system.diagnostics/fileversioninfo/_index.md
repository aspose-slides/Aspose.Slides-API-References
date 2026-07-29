---
title: FileVersionInfo
second_title: Aspose.Slides för C++ API-referens
description: "Tillhandahåller information om filversion. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av den här typen på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller påståendefel. Alltid omge den här klassen i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 1
url: /sv/system.diagnostics/fileversioninfo/
---
## FileVersionInfo klass


Tillhandahåller information om filversion. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Alltid omge denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class FileVersionInfo
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | Hämtar produktversionsfältet. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | Hämtar filversionsinformation; ej implementerad. |
## Se också

* Namnrymd [System::Diagnostics](../)
* Bibliotek [Aspose.Slides](../../)