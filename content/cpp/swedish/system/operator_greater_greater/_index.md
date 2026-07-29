---
title: operator>>()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en sträng från inmatningsströmmen med UTF-8-kodning.
type: docs
weight: 3004
url: /sv/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) funktion


Hämtar en sträng från inmatningsströmmen med UTF-8-kodning.

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| in | std::istream\& | Ett inmatningsströmobjekt (instansiering av **basic_ostream** med **char**). |
| str | [String](../string/)\& | En sträng att läsa från inmatningsströmmen. |

### Returvärde

En inmatningsström från vilken strängen extraherades.

## System::operator>>(std::wistream\&, String\&) funktion


Hämtar en sträng från inmatningsströmmen.

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| in | std::wistream\& | Ett inmatningsströmobjekt (instansiering av **basic_ostream** med ****wchar_t****). |
| str | [String](../string/)\& | En sträng att läsa från inmatningsströmmen. |

### Returvärde

En inmatningsström från vilken strängen extraherades.

## Se även

* Klass [String](../string/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)