---
title: WriteRaw()
second_title: Aspose.Slides C++ API Referencia
description: Amikor egy származtatott osztályban felülírják, nyers jelölőnyelvet ír kézzel egy karakterpufferből.
type: docs
weight: 287
url: /hu/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) metódus

Amikor egy leszármazott osztályban felülírják, nyers jelölőnyelvet ír kézzel egy karakterpufferból.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | A szöveget tartalmazó karaktertömb. |
| index | **int32_t** | A pufferben a szöveg írásának kezdőpozíciója. |
| count | **int32_t** | A írandó karakterek száma. |

## XmlWriter::WriteRaw(const String\&) metódus

Amikor egy leszármazott osztályban felülírják, nyers jelölőnyelvet ír kézzel egy karakterláncból.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) tartalmazza a írandó szöveget. |

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlWriter](../)
* Osztály [String](../../../system/string/)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)