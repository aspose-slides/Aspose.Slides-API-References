---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Försöker konvertera en given sträng till en instans av IPAddress-klassen.
type: docs
weight: 222
url: /sv/system.net/ipaddress/tryparse/
---
## IPAddress::TryParse(String, System::SharedPtr\<IPAddress\>\&) metod

Försöker konvertera en given sträng till en instans av klassen [IPAddress](../).

```cpp
static bool System::Net::IPAddress::TryParse(String ipString, System::SharedPtr<IPAddress> &address)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ipString | [String](../../../system/string/) | En sträng att tolka. |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../)\>\& | En instans där ett tolkad objekt kommer att tilldelas. |

### Returvärde

Sant när parsningen lyckas, annars falskt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [IPAddress](../)
* Namnområde [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)