---
title: CancellationToken
second_title: Aspose.Slides für C++ API-Referenz
description: Übermittelt die Benachrichtigung, dass Vorgänge abgebrochen werden sollen. Diese Klasse bietet einen Mechanismus für kooperative Abbrüche zwischen Threads, wobei ein Thread andere darüber informieren kann, dass ein Vorgang abgebrochen werden soll.
type: docs
weight: 14
url: /de/system.threading/cancellationtoken/
---
## CancellationToken Klasse


Übermittelt die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. Diese Klasse bietet einen Mechanismus für kooperative Abbrüche zwischen Threads, wodurch ein Thread andere darüber informieren kann, dass ein Vorgang abgebrochen werden soll.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Standardkonstruktor. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Ermittelt, ob dieses Token in den abgebrochenen Zustand versetzt werden kann. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Ermittelt, ob für dieses Token ein Abbruch angefordert wurde. |
| static [CancellationToken](./) [get_None](./get_none/)() | Gibt einen leeren [System::Threading::CancellationToken](./)-Wert zurück. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Registriert einen Rückruf, der aufgerufen wird, wenn ein Abbruch angefordert wird. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Wirft eine OperationCanceledException, wenn ein Abbruch angefordert wurde. |
## Bemerkungen



Ein [CancellationToken](./) kann nur über sein zugehöriges [CancellationTokenSource](../cancellationtokensource/) abgebrochen werden. 

## Siehe auch

* Namensraum [System::Threading](../)
* Bibliothek [Aspose.Slides](../../)