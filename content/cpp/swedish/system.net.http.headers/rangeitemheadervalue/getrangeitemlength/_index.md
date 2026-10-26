---
title: GetRangeItemLength()
second_title: Aspose.Slides för C++ API-referens
description: Omvandlar en given sträng från det angivna indexet till en instans av klassen RangeItemHeaderValue.
type: docs
weight: 92
url: /sv/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) metod


Omvandlar en given sträng från det angivna indexet till en instans av klassen [RangeItemHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [String](../../../system/string/) | En sträng att analysera. |
| startIndex | **int32_t** | En startposition för parsning. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | En instans där ett tolkat objekt kommer att tilldelas. |

## Returvärde

Returnerar längden på en tolkad delsträng, annars 0.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [RangeItemHeaderValue](../)
* Namnrymd [System::Net::Http::Headers](../../)
* Bibliotek [Aspose.Slides](../../../)