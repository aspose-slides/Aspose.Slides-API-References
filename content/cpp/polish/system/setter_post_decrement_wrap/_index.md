---
title: setter_post_decrement_wrap()
second_title: Dokumentacja API Aspose.Slides dla C++
description: Tłumacz przekształca wyrażenia postdekrementacyjne C# skierowane do własności klasy, które mają zdefiniowane setter i getter, w wywołanie tej funkcji.
type: docs
weight: 2874
url: /pl/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) funkcja

Tłumacz przekształca wyrażenia postdekrementacyjne C# skierowane do właściwości klasy, które mają zdefiniowane setter i getter, w wywołanie tej funkcji.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ właściwości |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Wskaźnik funkcji wskazujący na wolną funkcję getter właściwości |
| pSetter | void(*)(T) | Wskaźnik funkcji wskazujący na wolną funkcję setter właściwości |

### Wartość zwracana

Wartość właściwości przed inkrementacją

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) funkcja

Tłumacz przekształca wyrażenia postdekrementacyjne C# skierowane do właściwości instancji, które mają zdefiniowane setter i getter, w wywołanie tej funkcji (przeciążenie dla getter nie-const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ właściwości. |
| Host | – klasa instancji do modyfikacji |
| HostGet | – sam Host lub jego typ bazowy, w którym zdefiniowano getter właściwości |
| HostSet | – sam Host lub jego typ bazowy, w którym zdefiniowano setter właściwości |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Instancja, dla której wywoływane są gettery i settery. |
| pGetter | T(HostGet::*)() | Wskaźnik funkcji wskazujący na funkcję getter właściwości |
| pSetter | void(HostSet::*)(T) | Wskaźnik funkcji wskazujący na funkcję setter właściwości |

### Wartość zwracana

Wartość właściwości przed inkrementacją

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) funkcja

Tłumacz przekształca wyrażenia postdekrementacyjne C# skierowane do właściwości instancji, które mają zdefiniowane setter i getter, w wywołanie tej funkcji (przeciążenie dla getter const).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ właściwości. |
| Host | – klasa instancji do modyfikacji |
| HostConstGet | – sam Host lub jego typ bazowy, w którym zdefiniowano getter właściwości |
| HostSet | – sam Host lub jego typ bazowy, w którym zdefiniowano setter właściwości |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Instancja, dla której wywoływane są gettery i settery. |
| pGetter | T(HostConstGet::*)() const | Wskaźnik funkcji wskazujący na funkcję getter właściwości |
| pSetter | void(HostSet::*)(T) | Wskaźnik funkcji wskazujący na funkcję setter właściwości |

### Wartość zwracana

Wartość właściwości przed inkrementacją

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)