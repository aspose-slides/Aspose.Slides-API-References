---
title: TryEnter()
second_title: Référence de l'API Aspose.Slides pour C++
description: Tente d’acquérir un verrou exclusif sur l’objet spécifié. Non implémenté.
type: docs
weight: 27
url: /fr/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) méthode

Tente d’acquérir un verrou exclusif sur l’objet spécifié. Non implémenté.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) méthode

Tente d’acquérir un verrou exclusif sur l’objet spécifié et définit de façon atomique une valeur indiquant si le verrou a été acquis.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) méthode

Tente, pendant le nombre de millisecondes spécifié, d’acquérir un verrou exclusif sur l’objet spécifié. Non implémenté.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) méthode

Tente, pendant la durée spécifiée, d’acquérir un verrou exclusif sur l’objet spécifié. Non implémenté.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) méthode

Tente, pendant la durée spécifiée, d’acquérir un verrou exclusif sur l’objet spécifié et définit de façon atomique une valeur indiquant si le verrou a été acquis.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) méthode

Tente, pendant la durée spécifiée, d’acquérir un verrou exclusif sur l’objet spécifié et définit de façon atomique une valeur indiquant si le verrou a été acquis.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)