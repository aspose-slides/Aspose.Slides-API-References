---
title: LookupNamespace()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja a megadott előtaghoz tartozó névtér-URI-t.
type: docs
weight: 118
url: /hu/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) metódus

Visszaadja a megadott előtaghoz tartozó névtér-URI-t.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | A prefix, amelynek névtér-URI-ját fel akarja oldani. Az alapértelmezett névtérhez, adja meg a(z) [String::Empty](../../../system/string/empty/) értéket. |

### Visszatérési érték

A **prefix** névtér-URI-ja, vagy **nullptr**, ha nincs hozzárendelt névtér. A visszaadott karakterlánc atomizált. További információért az atomizált karakterláncokról lásd a(z) [XmlNameTable](../../xmlnametable/) osztályt.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNamespaceManager](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)