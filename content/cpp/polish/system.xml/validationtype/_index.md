---
title: ValidationType
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa typ walidacji do wykonania.
type: docs
weight: 729
url: /pl/system.xml/validationtype/
---
## ValidationType enum

Określa typ walidacji do wykonania.

```cpp
enum class ValidationType
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| None | 0 | Nie przeprowadza się żadnej walidacji i nie są zgłaszane błędy walidacji. To ustawienie tworzy parser zgodny z XML 1.0, nieprzeprowadzający walidacji. |
| Auto | 1 | Waliduje, jeśli zostaną znalezione informacje DTD lub schematu. |
| DTD | 2 | Waliduje zgodnie z DTD. |
| XDR | 3 | Waliduje zgodnie ze schematami XML-Data Reduced (XDR), w tym z wbudowanymi schematami XDR. Schematy XDR są rozpoznawane przy użyciu prefiksu przestrzeni nazw **x-schema** lub wartości [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | Waliduje zgodnie ze schematami języka definicji XML [Schema](../../system.xml.schema/) (XSD), w tym ze wbudowanymi schematami XML. Schematy XML są powiązane z identyfikatorami URI przestrzeni nazw albo przy użyciu atrybutu **schemaLocation**, albo przy użyciu dostarczonych **Schemas**. |

## Zobacz także

* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)