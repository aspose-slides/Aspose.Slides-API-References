---
title: XmlSchemaContentProcessing
second_title: Aspose.Slides C++ API hivatkozás
description: Információt nyújt a any és anyAttribute elemhelyettesítések érvényesítési módjáról.
type: docs
weight: 976
url: /hu/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enumeráció

Információt nyújt a **any** és **anyAttribute** elemhelyettesítések érvényesítési módjáról.

```cpp
enum class XmlSchemaContentProcessing
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| None | 0 | A dokumentumelemek nincsenek érvényesítve. |
| Skip | 1 | A dokumentumelemeknek jól formázott XML-ből kell állniuk, és a séma nem érvényesíti őket. |
| Lax | 2 | Ha a kapcsolódó sémát megtalálják, a dokumentumelemek érvényesítve lesznek. Különben nem kerül hiba dobásra. |
| Strict | 3 | A séma feldolgozónak meg kell találnia az adott névtérhez kapcsolódó sémát a dokumentumelemek érvényesítéséhez. |

## Lásd még

* Névtér [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)