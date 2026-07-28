---
title: setter_post_increment_wrap()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tłumacz zamienia wyrażenia post-inkrementacji C# skierowane do własności klasy, która ma zdefiniowane setter i getter, na wywołanie tej funkcji.
type: docs
weight: 2848
url: /pl/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) funkcja

Tłumacz zamienia wyrażenia post-inkrementacji C# skierowane do własności klasy, która ma zdefiniowane setter i getter, na wywołanie tej funkcji.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ własności |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pGetter | T(*)() | Wskaźnik funkcji wskazujący na wolną funkcję getter własności |
| pSetter | void(*)(T) | Wskaźnik funkcji wskazujący na wolną funkcję setter własności |

### Wartość zwracana

Wartość własności przed inkrementacją

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) funkcja

Tłumacz zamienia wyrażenia post-inkrementacji C# skierowane do własności instancji, która ma zdefiniowane setter i getter, na wywołanie tej funkcji (przeciążenie dla getter’a nie-stałego).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ własności. |
| Host | - klasa instancji, którą należy zmodyfikować |
| HostGet | - sam Host lub jego typ bazowy, w którym zdefiniowano getter własności |
| HostSet | - sam Host lub jego typ bazowy, w którym zdefiniowano setter własności |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| host | Host *const | Instancja, dla której wywoływane są gettery i settery. |
| pGetter | T(HostGet::*)() | Wskaźnik funkcji wskazujący na funkcję getter własności |
| pSetter | void(HostSet::*)(T) | Wskaźnik funkcji wskazujący na funkcję setter własności |

### Wartość zwracana

Wartość własności przed inkrementacją

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) funkcja

Tłumacz zamienia wyrażenia post-inkrementacji C# skierowane do własności instancji, która ma zdefiniowane setter i getter, na wywołanie tej funkcji (przeciążenie dla getter’a stałego).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ własności. |
| Host | - klasa instancji, którą należy zmodyfikować |
| HostConstGet | - sam Host lub jego typ bazowy, w którym zdefiniowano getter własności |
| HostSet | - sam Host lub jego typ bazowy, w którym zdefiniowano setter własności |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| host | Host *const | Instancja, dla której wywoływane są gettery i settery. |
| pGetter | T(HostConstGet::*)() const | Wskaźnik funkcji wskazujący na funkcję getter własności |
| pSetter | void(HostSet::*)(T) | Wskaźnik funkcji wskazujący na funkcję setter własności |

### Wartość zwracana

Wartość własności przed inkrementacją

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)