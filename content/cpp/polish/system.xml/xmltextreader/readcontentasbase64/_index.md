---
title: ReadContentAsBase64()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Odczytuje zawartość i zwraca binarne bajty po dekodowaniu Base64.
type: docs
weight: 638
url: /pl/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metoda


Odczytuje zawartość i zwraca **Base64** zdekodowane bajty binarne.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor, do którego ma zostać skopiowany wynikowy tekst. Ta wartość nie może być **nullptr**. |
| index | **int32_t** | Przesunięcie w buforze, od którego rozpocząć kopiowanie wyniku. |
| count | **int32_t** | Maksymalna liczba bajtów do skopiowania do bufora. Rzeczywista liczba skopiowanych bajtów jest zwracana przez tę metodę. |

### Wartość zwracana

Liczba bajtów zapisanych do bufora.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [XmlTextReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Library [Aspose.Slides](../../../)