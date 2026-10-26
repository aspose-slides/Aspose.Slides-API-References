---
title: GetEntity()
second_title: Aspose.Slides pro C++ API Reference
description: Mapuje URI na objekt obsahující skutečný zdroj.
type: docs
weight: 14
url: /cs/aspose.slides.import/htmlexternalresolver/getentity/
---
## HtmlExternalResolver::GetEntity(System::String) method

Mapuje URI na objekt obsahující skutečný zdroj.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::HtmlExternalResolver::GetEntity(System::String absoluteUri) override
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
* Třída [HtmlExternalResolver](../)
* Jmenný prostor [Aspose::Slides::Import](../../)
* Knihovna [Aspose.Slides](../../../)