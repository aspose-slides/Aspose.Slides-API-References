---
title: Register()
second_title: Aspose.Slides für C++ API-Referenz
description: Registriert einen Rückruf, der aufgerufen wird, wenn ein Abbruch angefordert wird.
type: docs
weight: 40
url: /de/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const Methode

Registriert einen Rückruf, der aufgerufen wird, wenn eine Abbruchanforderung gestellt wird.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | Die Action<> die ausgeführt wird, wenn eine Abbruchanforderung gestellt wird. |

### Rückgabewert

Ein [CancellationTokenRegistration](../../cancellationtokenregistration/) Objekt, das zum Abmelden des Rückrufs verwendet werden kann.

## Anmerkungen



Wenn bereits eine Abbruchanforderung gestellt wurde, wird der Rückruf sofort aufgerufen. 

Der Rückruf sollte kurzlebig und nicht blockierend sein, da er im Thread ausgeführt wird, der Cancel() auf dem [CancellationTokenSource](../../cancellationtokensource/) aufruft. 

## Siehe auch

* Typedef [Action](../../../system/action/)
* Klasse [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Klasse [CancellationToken](../)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)