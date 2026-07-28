---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Odczytuje element i dekoduje zawartość BinHex.
type: docs
weight: 482
url: /pl/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metoda

Odczytuje element i dekoduje zawartość BinHex.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor, do którego należy skopiować wynikowy tekst. Ta wartość nie może być **nullptr**. |
| index | **int32_t** | Przesunięcie w buforze, od którego rozpocząć kopiowanie wyniku. |
| count | **int32_t** | Maksymalna liczba bajtów do skopiowania do bufora. Rzeczywista liczba skopiowanych bajtów jest zwracana przez tę metodę. |

### Wartość zwracana

Liczba bajtów zapisanych do bufora.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [XmlNodeReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)