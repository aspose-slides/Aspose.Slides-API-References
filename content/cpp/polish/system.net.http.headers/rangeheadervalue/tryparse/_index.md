---
title: TryParse()
second_title: Aspose.Slides for C++ – odniesienie do API
description: Próbuje przekonwertować podany ciąg znaków na instancję klasy RangeHeaderValue.
type: docs
weight: 105
url: /pl/system.net.http.headers/rangeheadervalue/tryparse/
---
## RangeHeaderValue::TryParse(String, System::SharedPtr\<RangeHeaderValue\>\&) method


Próbuje przekonwertować podany ciąg znaków na instancję klasy [RangeHeaderValue](../).

```cpp
static bool System::Net::Http::Headers::RangeHeaderValue::TryParse(String input, System::SharedPtr<RangeHeaderValue> &parsedValue)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg znaków do przetworzenia. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeHeaderValue](../)\>\& | Instancja, do której zostanie przypisany sparsowany obiekt. |

### Wartość zwracana

Prawda, gdy parsowanie zakończy się pomyślnie, w przeciwnym razie fałsz.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [RangeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)