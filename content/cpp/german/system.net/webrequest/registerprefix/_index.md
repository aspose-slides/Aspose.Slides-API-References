---
title: RegisterPrefix()
second_title: Aspose.Slides für C++ API-Referenz
description: Registriert den WebRequest-Nachfahren für die angegebene URI.
type: docs
weight: 92
url: /de/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) Methode

Registriert den [WebRequest](../)-Nachfahren für die angegebene URI.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Der URI oder das URI-Präfix. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Erstellt neue Instanzen der [WebRequest](../)-Klasse. |

### Rückgabewert

True, wenn der [WebRequest](../)-Nachfolger erfolgreich für die angegebene URI registriert wurde, sonst false.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [IWebRequestCreate](../../iwebrequestcreate/)
* Klasse [WebRequest](../)
* Namensraum [System::Net](../../)
* Library [Aspose.Slides](../../../)