---
title: WriteRaw()
second_title: Aspose.Slides C++ API Referenciája
description: Nyers jelölőnyelvet ír kézzel egy karakterpufferből.
type: docs
weight: 417
url: /hu/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) metódus

Nyers jelölőnyelvet ír kézzel egy karakterpufferből.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | A szöveget tartalmazó karaktertömb. |
| index | **int32_t** | A pufferen belüli pozíció, amely a szöveg írásának kezdetét jelzi. |
| count | **int32_t** | A kiírandó karakterek száma. |

## XmlTextWriter::WriteRaw(const String\&) metódus

Nyers jelölőnyelvet ír kézzel egy karakterláncból.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) tartalmazza a kiírandó szöveget. |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlTextWriter](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)