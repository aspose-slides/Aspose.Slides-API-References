---
title: RegisterPrefix()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Rejestruje potomka WebRequest dla określonego URI.
type: docs
weight: 92
url: /pl/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) metoda

Rejestruje potomka [WebRequest](../) dla określonego URI.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Adres URI lub prefiks URI. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Tworzy nowe instancje klasy [WebRequest](../). |

### Wartość zwracana

True, gdy potomka [WebRequest](../) zostanie pomyślnie zarejestrowany dla określonego URI, w przeciwnym razie false.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [IWebRequestCreate](../../iwebrequestcreate/)
* Klasa [WebRequest](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)