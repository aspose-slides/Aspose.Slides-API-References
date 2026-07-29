---
title: RegisterPrefix()
second_title: Aspose.Slides för C++ API-referens
description: Registrerar WebRequest-avkomman för den angivna URI:n.
type: docs
weight: 92
url: /sv/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) metod

Registrerar den [WebRequest](../) avkomman för den angivna URI:n.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | URI:n eller URI-prefixet. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Skapar nya instanser av klassen [WebRequest](../). |

### Returvärde

Sant när [WebRequest](../)-avkomman har registrerats framgångsrikt för den angivna URI:n, annars falskt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [IWebRequestCreate](../../iwebrequestcreate/)
* Klass [WebRequest](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)