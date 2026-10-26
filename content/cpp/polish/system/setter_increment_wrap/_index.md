---
title: setter_increment_wrap()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tłumacz przetwarza wyrażenia inkrementacji języka C# skierowane do własności klasy, która ma zdefiniowane setter i getter, na wywołanie tej funkcji.
type: docs
weight: 2835
url: /pl/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) funkcja

Tłumacz przetwarza wyrażenia inkrementacji języka C# skierowane do własności klasy, która ma zdefiniowane setter i getter, na wywołanie tej funkcji.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ własności |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Wskaźnik funkcji wskazujący na wolną funkcję getter własności |
| pSetter | void(*)(T) | Wskaźnik funkcji wskazujący na wolną funkcję setter własności |

### Wartość zwracana

Zwiększona wartość własności

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) funkcja

Tłumacz przetwarza wyrażenia inkrementacji języka C# skierowane do własności klasy, która ma zdefiniowane setter i getter, na wywołanie tej funkcji.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ własności |
| Host | - klasa instancji do modyfikacji |
| HostGet | - Host sam, albo jego typ bazowy, w którym zdefiniowany jest getter własności |
| HostSet | - Host sam, albo jego typ bazowy, w którym zdefiniowany jest setter własności |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Wskaźnik do obiektu, którego własność ma być zwiększona |
| pGetter | T(HostGet::*)() | Wskaźnik funkcji wskazujący na metodę getter własności |
| pSetter | void(HostSet::*)(T) | Wskaźnik funkcji wskazujący na metodę setter własności |

### Wartość zwracana

Zwiększona wartość własności

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)