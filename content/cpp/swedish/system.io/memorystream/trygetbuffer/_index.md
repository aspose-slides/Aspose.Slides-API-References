---
title: TryGetBuffer()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar arrayen av osignerade byte som detta flöde skapades från.
type: docs
weight: 170
url: /sv/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) metod


Returnerar array av osignerade byte från vilken detta flöde skapades.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | bytearray - utparameter. När den här metoden returnerar true, bytearraysegmentet från vilket detta flöde skapades; när den här metoden returnerar false, sätts den här parametern till standardvärdet. |

### Returvärde

True om konverteringen lyckades.

## Se även

* Klass [ArraySegment](../../../system/arraysegment/)
* Klass [MemoryStream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)