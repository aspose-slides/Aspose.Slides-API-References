---
title: ExceptionWrapper()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een null-instance van de ExceptionWrapper-klasse die geen uitzondering vertegenwoordigt.
type: docs
weight: 14
url: /nl/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) constructor


Construeert een null-instance van de [ExceptionWrapper](../)-klasse die geen uitzondering vertegenwoordigt.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) constructor


Construeert een instance van de [ExceptionWrapper](../)-klasse die de meegegeven pointer bevat.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Slimme pointer naar de instance van de Exception-klasse. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) constructor


Copy-constructor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Andere instance van de wrapper-klasse die gekopieerd moet worden. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) constructor


Move-constructor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Andere instance van de wrapper-klasse die verplaatst moet worden. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) constructor


Constructor die parameters doorstuurt naar de constructors van de Exception-klasse en een slimme pointer maakt die een nieuw Exception-klasse-instance bevat.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Zie ook

* Typedef [ExceptionPtr](../../exceptionptr/)
* Klasse [ExceptionWrapper](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)