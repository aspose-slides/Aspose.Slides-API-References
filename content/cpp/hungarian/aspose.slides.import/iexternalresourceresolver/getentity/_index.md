---
title: GetEntity()
second_title: Aspose.Slides C++ API referencia
description: Egy URI-t egy a tényleges erőforrást tartalmazó objektumra képez le.
type: docs
weight: 14
url: /hu/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) metódus

Egy URI-t egy a tényleges erőforrást tartalmazó objektumra képez le.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Az objektum abszolút URI-ja. |

### Visszatérési érték

Egy [System::IO::Stream](../../../system.io/stream/) objektum vagy null, ha az erőforrás nem streamelhető.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [String](../../../system/string/)
* Osztály [IExternalResourceResolver](../)
* Névtér [Aspose::Slides::Import](../../)
* Könyvtár [Aspose.Slides](../../../)