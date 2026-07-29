---
title: InternalAdd()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till den specificerade kakan i samlingen.
type: docs
weight: 118
url: /sv/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) metod

Lägger till den specificerade kakan i samlingen.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Kakan att lägga till. |
| isStrict | **bool** | Sant när den specificerade kakan måste ersätta den gamla, annars falskt. |

### Returvärde

0 när den specificerade kakan ersatte den gamla, annars 1.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Cookie](../../cookie/)
* Klass [CookieCollection](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)