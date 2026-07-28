---
title: ReadValueChunk()
second_title: Aspose.Slides dla C++ – referencja API
description: Odczytuje duże strumienie tekstu osadzone w dokumencie XML.
type: docs
weight: 807
url: /pl/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) metoda


Odczytuje duże strumienie tekstu osadzone w dokumencie XML.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Tablica znaków służąca jako bufor, do którego zapisywana jest zawartość tekstowa. Ta wartość nie może być **nullptr**. |
| index | **int32_t** | Offset w buforze, od którego [XmlReader](../) może rozpocząć kopiowanie wyników. |
| count | **int32_t** | Maksymalna liczba znaków do skopiowania do bufora. Rzeczywista liczba skopiowanych znaków jest zwracana przez tę metodę. |

### Wartość zwracana

Liczba znaków odczytanych do bufora. Zero jest zwracane, gdy nie ma więcej treści tekstowej.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)