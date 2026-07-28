---
title: ReadChars()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Odczytuje zawartość tekstową elementu do bufora znaków. Ta metoda jest zaprojektowana do odczytywania dużych strumieni osadzonego tekstu poprzez wielokrotne wywoływanie.
type: docs
weight: 755
url: /pl/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metoda


Odczytuje zawartość tekstową elementu do bufora znaków. Ta metoda została zaprojektowana do odczytywania dużych strumieni osadzonego tekstu poprzez wielokrotne wywoływanie.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Tablica znaków służąca jako bufor, do którego zapisywana jest zawartość tekstowa. |
| index | **int32_t** | Pozycja w **buffer**, od której metoda może rozpocząć zapisywanie zawartości tekstowej. |
| count | **int32_t** | Liczba znaków do zapisania w **buffer**. |

### Wartość zwracana

Liczba odczytanych znaków. Może być równa 0, jeśli czytnik nie jest ustawiony na elemencie lub nie ma już żadnej zawartości tekstowej do zwrócenia w bieżącym kontekście.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [XmlTextReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)