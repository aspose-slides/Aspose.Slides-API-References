---
title: Func()
second_title: Aspose.Slides voor C++ API-referentie
description: Standaardconstructor die een null-Func maakt.
type: docs
weight: 1
url: /nl/system/func/func/
---
## Func::Func() constructor

Standaardconstructor die een null-Func maakt.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) constructor

Constructor die een [Func](../) object maakt en een waarde (ofwel de daadwerkelijke callback of nullptr) eraan toekent.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Argumenttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg | T\&& | Argument. |

## Func::Func(const Func\&) constructor

Kopieerconstructor.

```cpp
System::Func<Args>::Func(const Func &func)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) om data van te kopiëren. |

## Func::Func(Func\&&) constructor

Move-constructor.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) om data van te verplaatsen. |

## Zie ook

* Klasse [Func](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)