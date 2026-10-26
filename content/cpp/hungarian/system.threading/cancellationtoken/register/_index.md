---
title: Register()
second_title: Aspose.Slides for C++ API Referencia
description: Regisztrál egy visszahívást, amely akkor kerül meghívásra, amikor a leállítás kérése megtörténik.
type: docs
weight: 40
url: /hu/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const method

Egy visszahívást regisztrál, amely akkor kerül meghívásra, amikor a leállítás kérése megtörténik.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | Az Action<> amelyet a leállítás kérése esetén végre kell hajtani. |

### Visszatérési érték

Egy [CancellationTokenRegistration](../../cancellationtokenregistration/) objektum, amely a visszahívás letiltására használható.

## Megjegyzések

Ha a leállítás már korábban kérve lett, a visszahívás azonnal meghívásra kerül.

A visszahívásnak rövidnek és nem blokkolónak kell lennie, mivel a [CancellationTokenSource](../../cancellationtokensource/)-on a Cancel() hívó szálon kerül végrehajtásra.

## Lásd még

* Typedef [Action](../../../system/action/)
* Osztály [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Osztály [CancellationToken](../)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)