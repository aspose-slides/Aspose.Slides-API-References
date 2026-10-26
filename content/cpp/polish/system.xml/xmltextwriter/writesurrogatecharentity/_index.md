---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: Generuje i zapisuje encję znaku surrogatowego dla pary znaków surrogatowych.
type: docs
weight: 391
url: /pl/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) metoda

Generuje i zapisuje encję znaku surrogatowego dla pary znaków surrogatowych.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lowChar | char16_t | Niski surrogat. Musi to być wartość pomiędzy **0xDC00** a **0xDFFF**. |
| highChar | char16_t | Wysoki surrogat. Musi to być wartość pomiędzy **0xD800** a **0xDBFF**. |

## Zobacz także

* Klasa [XmlTextWriter](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)