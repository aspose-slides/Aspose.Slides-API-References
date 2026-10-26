---
title: CopyTo()
second_title: Aspose.Slides för C++ API-referens
description: Kopierar tecken i strängen till befintliga array-element. Ingen storleksändring utförs.
type: docs
weight: 430
url: /sv/system/string/copyto/
---
## String::CopyTo(int, const ArrayPtr\<char_t\>\&, int, int) const metod


Kopierar tecken i strängen till befintliga array-element. Ingen resize görs.

```cpp
void System::String::CopyTo(int sourceIndex, const ArrayPtr<char_t> &destination, int destinationIndex, int count) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceIndex | int | Index i strängen att börja läsa från. |
| destination | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Destinationsarray. |
| destinationIndex | int | Index i arrayen att börja skriva från. |
| count | int | Antal tecken att kopiera. |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [String](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)