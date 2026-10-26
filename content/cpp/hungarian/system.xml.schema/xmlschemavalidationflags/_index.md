---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides C++ API-referencia
description: Megadja a séma validálási beállításokat, amelyeket az XmlSchemaValidator és az XmlReader osztályok használnak.
type: docs
weight: 1054
url: /hu/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

Megadja a sémával kapcsolatos érvényesítési beállításokat, amelyeket a [XmlSchemaValidator](../xmlschemavalidator/) és [XmlReader](../../system.xml/xmlreader/) osztályok használnak.

```cpp
enum class XmlSchemaValidationFlags
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| None | 0 | Ne dolgozza fel az azonossági megszorításokat, beágyazott sémákat, sémahelyeszközöket, vagy ne jelentse a séma-érvényesítési figyelmeztetéseket. |
| ProcessInlineSchema | 1 | Feldolgozza a validálás során felbukkanó beágyazott sémákat. |
| ProcessSchemaLocation | 2 | Feldolgozza a validálás során felbukkanó sémahelyeszközöket (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**). |
| ReportValidationWarnings | 4 | Jelenti a validálás során felbukkanó séma-érvényesítési figyelmeztetéseket. |
| ProcessIdentityConstraints | 8 | Feldolgozza a validálás során felbukkanó azonossági megszorításokat (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**). |
| AllowXmlAttributes | 16 | Lehetővé teszi az xml:* attribútumokat is, ha azok nincsenek definiálva a sémában. Az attribútumok az adattípusuk alapján kerülnek érvényesítésre. |

## Lásd még

* Névtér [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)