---
title: Enter()
second_title: Aspose.Slides for C++ API-referentie
description: Verkrijgt een exclusieve lock op een opgegeven object.
type: docs
weight: 1
url: /nl/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) methode


Verkrijgt een exclusieve lock op een opgegeven object.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Het object waarop de monitorvergrendeling moet worden verworven. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) methode


Verkrijgt een exclusieve lock op het opgegeven object, en stelt atomisch een waarde in die aangeeft of de lock is genomen.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Monitor](../)
* Naamruimte [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)