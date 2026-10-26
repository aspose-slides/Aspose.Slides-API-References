---
title: RegisterPrefix()
second_title: Aspose.Slides pro C++ API Referenční příručka
description: Registruje potomka WebRequest pro zadané URI.
type: docs
weight: 92
url: /cs/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) metoda


Registruje potomka [WebRequest](../) pro zadané URI.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | URI nebo předpona URI. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Vytváří nové instance třídy [WebRequest](../). |

### Návratová hodnota

True, pokud je potomek [WebRequest](../) úspěšně zaregistrován pro zadané URI, jinak false.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [IWebRequestCreate](../../iwebrequestcreate/)
* Třída [WebRequest](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)