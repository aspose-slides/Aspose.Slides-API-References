---
title: GetEntity()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Mapuje URI do obiektu zawierającego rzeczywisty zasób.
type: docs
weight: 14
url: /pl/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) metoda

Mapuje URI do obiektu zawierającego rzeczywisty zasób.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Absolutny URI do obiektu. |

### Wartość zwracana

Obiekt [System::IO::Stream](../../../system.io/stream/) lub null, jeśli zasób nie może być strumieniowany.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ExternalResourceResolver](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)