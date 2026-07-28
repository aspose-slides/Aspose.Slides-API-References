---
title: GetEntity()
second_title: Aspose.Slides C++ API-referencia
description: Leképezi egy URI-t egy objektumra, amely a tényleges erőforrást tartalmazza.
type: docs
weight: 14
url: /hu/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) metódus

Leképezi a URI-t egy objektumra, amely a tényleges erőforrást tartalmazza.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Az objektumhoz tartozó abszolút URI. |

### Visszatérési érték

[System::IO::Stream](../../../system.io/stream/) objektum vagy null, ha az erőforrás nem streamelhető.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [String](../../../system/string/)
* Osztály [ExternalResourceResolver](../)
* Névtér [Aspose::Slides::Import](../../)
* Könyvtár [Aspose.Slides](../../../)