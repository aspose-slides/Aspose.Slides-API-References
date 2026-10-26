---
title: RegisterPrefix()
second_title: Aspose.Slides voor C++ API-referentie
description: Registreert de WebRequest-afstammeling voor de opgegeven URI.
type: docs
weight: 92
url: /nl/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) methode

Registreert de [WebRequest](../) afstammeling voor de opgegeven URI.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | De URI of het URI-voorvoegsel. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Maakt nieuwe instanties van de [WebRequest](../) klasse. |

### Returnwaarde

True wanneer de [WebRequest](../) afstammeling succesvol is geregistreerd voor de opgegeven URI, anders false.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [IWebRequestCreate](../../iwebrequestcreate/)
* Klasse [WebRequest](../)
* Namespace [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)