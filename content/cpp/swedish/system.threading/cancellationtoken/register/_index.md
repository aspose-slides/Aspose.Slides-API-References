---
title: Register()
second_title: Aspose.Slides för C++ API-referens
description: Registrerar en återuppringning som kommer att anropas när avbrytning begärs.
type: docs
weight: 40
url: /sv/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const metod

Registrerar en återuppringning som kommer att anropas när avbrytning begärs.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | Den Action<> som ska köras när avbrytning begärs. |

### Returvärde

Ett [CancellationTokenRegistration](../../cancellationtokenregistration/)-objekt som kan användas för att avregistrera återuppringningen.

## Anmärkningar

Om avbrytning redan har begärts kommer återuppringningen att anropas omedelbart. 

Återuppringningen bör vara kortlivad och icke-blockerande eftersom den kommer att köras på den tråd som anropar Cancel() på [CancellationTokenSource](../../cancellationtokensource/). 

## Se även

* Typdefinition [Action](../../../system/action/)
* Klass [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Klass [CancellationToken](../)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)