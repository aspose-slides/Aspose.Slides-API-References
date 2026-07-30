---
title: GetEntity()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Mapuje URI na objekt obsahující skutečný zdroj.
type: docs
weight: 14
url: /cs/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) metoda

Mapuje URI na objekt obsahující skutečný zdroj.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Absolutní URI k objektu. |

### Návratová hodnota

Objekt [System::IO::Stream](../../../system.io/stream/) nebo null, pokud nelze zdroj streamovat.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../../system.io/stream/)
* Třída [String](../../../system/string/)
* Třída [ExternalResourceResolver](../)
* Jmenný prostor [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)