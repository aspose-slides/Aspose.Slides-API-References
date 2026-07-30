---
title: GetEntity()
second_title: Aspose.Slides pro C++ API Reference
description: Mapuje URI na objekt obsahující skutečný zdroj.
type: docs
weight: 14
url: /cs/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) metoda

Mapuje URI na objekt obsahující skutečný zdroj.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Absolutní URI k objektu. |

### Návratová hodnota

Objekt [System::IO::Stream](../../../system.io/stream/) nebo null, pokud zdroj nelze streamovat.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../../system.io/stream/)
* Třída [String](../../../system/string/)
* Třída [IExternalResourceResolver](../)
* Jmenný prostor [Aspose::Slides::Import](../../)
* Knihovna [Aspose.Slides](../../../)