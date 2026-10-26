---
title: idx_get()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en cookie från cookie-samlingen på det angivna indexet.
type: docs
weight: 40
url: /sv/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) metod


Returnerar en cookie från cookie-samlingen på det angivna indexet.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Indexet för en cookie som måste returneras. |

### Returvärde

En cookie på det angivna indexet.

## CookieCollection::idx_get(String) metod


Returnerar en cookie från cookie-samlingen efter angivet namn.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Namnet på en cookie som måste returneras. |

### Returvärde

En cookie från cookie-samlingen efter angivet namn när den hittas, annars nullptr.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Cookie](../../cookie/)
* Klass [CookieCollection](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)