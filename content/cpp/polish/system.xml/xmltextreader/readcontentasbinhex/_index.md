---
title: ReadContentAsBinHex()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Odczytuje zawartość i zwraca zdekodowane bajty binarne w formacie BinHex.
type: docs
weight: 664
url: /pl/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metoda

Odczytuje zawartość i zwraca **BinHex** zdekodowane bajty binarne.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [XmlTextReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)