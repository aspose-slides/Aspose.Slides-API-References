---
title: ReadContentAsBase64()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Odczytuje zawartość i zwraca binarne bajty zdekodowane z Base64.
type: docs
weight: 573
url: /pl/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metoda

Odczytuje zawartość i zwraca bajty binarne zdekodowane z Base64.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor, do którego ma zostać skopiowany wynikowy tekst. Ta wartość nie może być **nullptr**. |
| index | **int32_t** | Przesunięcie w buforze, od którego rozpocząć kopiowanie wyniku. |
| count | **int32_t** | Maksymalna liczba bajtów do skopiowania do bufora. Rzeczywista liczba skopiowanych bajtów jest zwracana przez tę metodę. |

### Wartość zwracana

Liczba bajtów zapisanych do bufora.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [XmlValidatingReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)