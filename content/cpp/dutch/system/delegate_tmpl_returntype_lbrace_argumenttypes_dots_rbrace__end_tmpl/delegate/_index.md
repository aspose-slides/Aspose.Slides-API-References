---
title: Delegate()
second_title: Aspose.Slides voor C++ API-referentie
description: Standaardconstructor. Construeert het delegate-object dat nergens naar verwijst.
type: docs
weight: 1
url: /nl/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() methode


Standaardconstructor. Construeert het delegate-object dat nergens naar verwijst.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) methode




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) methode


Verplaatsende copy-constructor. Neemt het eigendom over van een entiteit waarnaar de opgegeven delegate verwijst.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| o | Delegate\&& | Het Delegate-object om de waarnaar verwezen entiteit van te verplaatsen |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) methode


Constructor. Construeert een delegate-object vanuit de opgegeven pointer naar een vrije functie of statische methode.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| De | type van de functie- of statische-methoden-pointer die door de constructor als argument wordt geaccepteerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| function | T | Pointer naar een functie of een statische methode waardoor de nieuw aangemaakte Delegate-instantie naar zal verwijzen |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) methode


Constructor. Construeert een delegate vanuit de opgegeven pointer naar het functie-object gegenereerd door std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| De | type van het functie-object gegenereerd door std::bind() dat door de constructor als argument wordt geaccepteerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| function | T | Pointer naar een "bind-expressie" – een functiereferentie gegenereerd door std::bind() – waarnaar de nieuw aangemaakte Delegate-instantie zal wijzen |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) methode


Constructor. Construeert een delegate vanuit het opgegeven functie-object.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | het type van het functie-object dat door de constructor als argument wordt geaccepteerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functor_tag | int | Een dummy-integerwaarde; dit argument wordt gebruikt om ambiguïteit op te lossen |
| functor | T\& | Een functie-object waarnaar de nieuw geconstrueerde delegate zal wijzen |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) methode


Verplaatsende constructor. Construeert een delegate vanuit het opgegeven functie-object.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | het type van het functie-object dat door de constructor als argument wordt geaccepteerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functor_tag | long | Een dummy-integerwaarde; dit argument wordt gebruikt om ambiguïteit op te lossen |
| functor | T\&& | Een functie-object waarnaar de nieuw geconstrueerde delegate zal wijzen |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) methode


Constructor. Construeert een delegate die wijst naar de opgegeven niet-statische methode van het opgegeven object.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| MemberType | het type van de niet-statische methode dat de constructor accepteert als argument |
| ClassType | het type van het object dat door de constructor als argument wordt geaccepteerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| member | MemberType ClassType::* | Een pointer naar de niet-statische methode waarnaar de nieuw aangemaakte delegate zal wijzen |
| obj | ClassType * | Een pointer naar een object waarvan de lidmethode door de nieuw aangemaakte delegate zal worden aangewezen |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) methode


Constructor. Construeert een delegate die wijst naar de opgegeven niet-statische methode van het opgegeven object.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| MemberType | het type van de niet-statische methode dat de constructor accepteert als argument |
| ClassType | het type van het object dat door de constructor als argument wordt geaccepteerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| member | MemberType MemberClass::* | Een pointer naar de niet-statische methode waarnaar de nieuw aangemaakte delegate zal wijzen |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Een gedeelde pointer naar een object waarvan de lidmethode door de nieuw aangemaakte delegate zal worden aangewezen |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) methode


Construeert een delegate-object dat wijst naar een std::function functie-object.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| R | het retourtype van het functie-object dat door de constructor als argument wordt geaccepteerd |
| Args | de argumentenlijst van het functie-object dat door de constructor als argument wordt geaccepteerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Een functie-object waarnaar het nieuw aangemaakte delegate-object zal wijzen |

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)