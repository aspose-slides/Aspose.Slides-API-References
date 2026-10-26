---
title: Dispose()
second_title: Aspose.Slides för C++ API-referens
description: Avslutar registreringen och tar bort återanropet från den associerade CancellationTokenSource. Efter att ha anropat denna metod kommer det registrerade återanropet inte längre att anropas när den associerade CancellationTokenSource avbryts.
type: docs
weight: 1
url: /sv/system.threading/cancellationtokenregistration/dispose/
---
## CancellationTokenRegistration::Dispose() metod

Avslutar registreringen och tar bort återanropet från den associerade [CancellationTokenSource](../../cancellationtokensource/). Efter att ha anropat denna metod kommer det registrerade återanropet inte längre att anropas när den associerade [CancellationTokenSource](../../cancellationtokensource/) avbryts.

```cpp
void System::Threading::CancellationTokenRegistration::Dispose()
```

## Anmärkningar

Det är säkert att anropa denna metod flera gånger - efterföljande anrop kommer inte att ha någon effekt.

## Se även

* Klass [CancellationTokenRegistration](../)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)