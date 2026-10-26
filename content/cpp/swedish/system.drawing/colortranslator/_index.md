---
title: ColorTranslator
second_title: Aspose.Slides för C++ API-referens
description: "Utför färgöversättningar. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Packa alltid in denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 66
url: /sv/system.drawing/colortranslator/
---
## ColorTranslator klass


Utför färgöversättningar. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller påståendefel. Packa alltid in denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ColorTranslator
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Konverterar den angivna HTML-färgrepresentationen till motsvarande [Color](../color/)-objekt. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Konverterar den angivna [Windows](../../system.windows/)-färgen till motsvarande [Color](../color/)-objekt. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Konverterar det angivna [Color](../color/)-objektet till strängrepresentationen av motsvarande HTML-färg. |
## Se även

* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)