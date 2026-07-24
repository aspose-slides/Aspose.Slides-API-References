---
title: Enter()
second_title: Aspose.Slides für C++ API-Referenz
description: Erwirbt eine exklusive Sperre für ein angegebenes Objekt.
type: docs
weight: 1
url: /de/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) Methode


Erwirbt eine exklusive Sperre für ein angegebenes Objekt.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Das Objekt, für das die Monitor-Sperre erworben werden soll. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) Methode


Erwirbt eine exklusive Sperre für das angegebene Objekt und setzt atomar einen Wert, der anzeigt, ob die Sperre übernommen wurde.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Monitor](../)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)