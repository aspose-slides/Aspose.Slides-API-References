---
title: WriteRaw()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Gdy zostanie przesłonięta w klasie pochodnej, zapisuje surowy znacznik ręcznie z bufora znaków.
type: docs
weight: 287
url: /pl/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) metoda

Gdy zostanie przesłonięta w klasie pochodnej, zapisuje surowy znacznik ręcznie z bufora znaków.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Tablica znaków zawierająca tekst do zapisania. |
| index | **int32_t** | Pozycja w buforze wskazująca początek tekstu do zapisania. |
| count | **int32_t** | Liczba znaków do zapisania. |

## XmlWriter::WriteRaw(const String\&) metoda

Gdy zostanie przesłonięta w klasie pochodnej, zapisuje surowy znacznik ręcznie z łańcucha znaków.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) zawierający tekst do zapisania. |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [XmlWriter](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml](../../)
* Library [Aspose.Slides](../../../)