---
title: TryGetValues()
second_title: Aspose.Slides för C++ API-referens
description: Försöker hämta motsvarande värden med det angivna namnet.
type: docs
weight: 66
url: /sv/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) metod

Försöker hämta motsvarande värden med det angivna namnet.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Header-namnet. |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | En instans där motsvarande värden kommer att tilldelas. |

### Returvärde

True när header-värdena hittas med det angivna namnet, annars false.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klass [HttpHeaders](../)
* Namnrymd [System::Net::Http::Headers](../../)
* Bibliotek [Aspose.Slides](../../../)