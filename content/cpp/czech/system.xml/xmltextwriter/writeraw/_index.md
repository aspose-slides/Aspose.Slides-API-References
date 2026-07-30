---
title: WriteRaw()
second_title: Aspose.Slides pro C++ API Reference
description: Zapisuje surový markup ručně z bufferu znaků.
type: docs
weight: 417
url: /cs/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) metoda


Zapisuje surový markup ručně z bufferu znaků.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Pole znaků obsahující text k zápisu. |
| index | **int32_t** | Pozice v bufferu označující začátek textu k zápisu. |
| count | **int32_t** | Počet znaků k zápisu. |

## XmlTextWriter::WriteRaw(const String\&) metoda


Zapisuje surový markup ručně z řetězce.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) obsahující text k zápisu. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)