---
title: Warning()
second_title: Aspose.Slides für C++ API-Referenz
description: Callback-Methode, die eine Warnung empfängt und entscheidet, ob der Vorgang abgebrochen werden soll.
type: docs
weight: 1
url: /de/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) Methode

Callback-Methode, die eine Warnung empfängt und entscheidet, ob der Vorgang abgebrochen werden soll.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Zu verarbeitende Warnung. |

### Rückgabewert

Abbruchentscheidung [ReturnAction](../../returnaction/).

## Siehe auch

* Aufzählung [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IWarningInfo](../../iwarninginfo/)
* Klasse [IWarningCallback](../)
* Namensraum [Aspose::Slides::Warnings](../../)
* Bibliothek [Aspose.Slides](../../../)