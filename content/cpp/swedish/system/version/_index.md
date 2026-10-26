---
title: Version
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett versionsnummer. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klass för att hantera objekt av denna typ."
type: docs
weight: 1470
url: /sv/system/version/
---
## Version klass


Representerar ett versionsnummer. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
class Version
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Jämför versionerna som representeras av det aktuella objektet och det angivna objektet. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Fastställer om versionsnumren som representeras av det aktuella och det angivna objektet är lika. |
| int [get_Build](./get_build/)() const | Returnerar byggnumret. |
| int [get_Major](./get_major/)() const | Returnerar huvudversionen. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Returnerar det högsta 16-bitarsvärdet för revisionsnumret. |
| int [get_Minor](./get_minor/)() const | Returnerar delversionen. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Returnerar det lägsta 16-bitarsvärdet för revisionsnumret. |
| int [get_Revision](./get_revision/)() const | Returnerar revisionsnumret. |
| int [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | Konverterar strängrepresentationen av ett versionsnummer till en motsvarande instans av [Version](./) klass. |
| [String](../string/) [ToString](./tostring/)() const | Returnerar strängrepresentationen av versionsnumret som representeras av det aktuella objektet. |
| [String](../string/) [ToString](./tostring/)(int) const | Returnerar strängrepresentationen av det angivna antalet sektioner av versionsnumret som representeras av det aktuella objektet. |
|  [Version](./version/)(int, int, int, int) | Skapar en instans som representerar de angivna huvud-, del-, bygg- och revisionsvärdena. |
|  [Version](./version/)(int, int, int) | Skapar en instans som representerar de angivna huvud-, del- och byggvärdena. |
|  [Version](./version/)(int, int) | Skapar en instans som representerar de angivna huvud- och värdena. |
|  [Version](./version/)(const [String](../string/)\&) | Skapar en instans som representerar versionsnumret som en sträng. |
|  [Version](./version/)() | Skapar en instans som representerar versionsnummer 0.0.-1.-1. |
## Se även

* Namespace [System](../)
* Library [Aspose.Slides](../../)