---
title: Register()
second_title: Aspose.Slides pro referenci API C++
description: Registruje zpětné volání, které bude vyvoláno, když je požadováno zrušení.
type: docs
weight: 40
url: /cs/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const metoda


Registruje zpětné volání, které bude vyvoláno, když je požadováno zrušení.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | Akce<> k provedení, když je požadováno zrušení. |

### Návratová hodnota

Objekt [CancellationTokenRegistration](../../cancellationtokenregistration/), který lze použít k odregistrování zpětného volání.
## Poznámky



Pokud bylo zrušení již požadováno, zpětné volání bude vyvoláno okamžitě. 

Zpětné volání by mělo být krátkodobé a neblokující, protože bude provedeno ve vlákně, které volá Cancel() na [CancellationTokenSource](../../cancellationtokensource/). 

## Viz také

* Typedef [Action](../../../system/action/)
* Třída [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Třída [CancellationToken](../)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)