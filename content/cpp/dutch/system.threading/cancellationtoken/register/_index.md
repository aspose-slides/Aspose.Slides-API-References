---
title: Register()
second_title: Aspose.Slides voor C++ API-referentie
description: Registreert een callback die wordt aangeroepen wanneer annulering wordt aangevraagd.
type: docs
weight: 40
url: /nl/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const methode

Registreert een callback die wordt aangeroepen wanneer annulering wordt aangevraagd.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | De Action<> om uit te voeren wanneer annulering wordt aangevraagd. |

### Retourwaarde

Een [CancellationTokenRegistration](../../cancellationtokenregistration/) object dat kan worden gebruikt om de callback af te melden.

## Opmerkingen

Als annulering al is aangevraagd, wordt de callback onmiddellijk aangeroepen.

De callback moet van korte duur en niet-blokkerend zijn, aangezien deze wordt uitgevoerd op de thread die Cancel() aanroept op de [CancellationTokenSource](../../cancellationtokensource/).

## Zie ook

* Typedef [Action](../../../system/action/)
* Klasse [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Klasse [CancellationToken](../)
* Naamruimte [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)