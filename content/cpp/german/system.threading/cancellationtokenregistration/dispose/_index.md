---
title: Dispose()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt die Registrierung und entfernt den Rückruf aus dem zugehörigen CancellationTokenSource. Nach dem Aufruf dieser Methode wird der registrierte Rückruf nicht mehr aufgerufen, wenn der zugehörige CancellationTokenSource abgebrochen wird.
type: docs
weight: 1
url: /de/system.threading/cancellationtokenregistration/dispose/
---
## CancellationTokenRegistration::Dispose() Methode

Entfernt die Registrierung und entfernt den Rückruf aus dem zugehörigen [CancellationTokenSource](../../cancellationtokensource/). Nach dem Aufruf dieser Methode wird der registrierte Rückruf nicht mehr aufgerufen, wenn der zugehörige [CancellationTokenSource](../../cancellationtokensource/) abgebrochen wird.

```cpp
void System::Threading::CancellationTokenRegistration::Dispose()
```

## Hinweise

Es ist sicher, diese Methode mehrmals aufzurufen - nachfolgende Aufrufe haben keine Wirkung.

## Siehe auch

* Klasse [CancellationTokenRegistration](../)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)