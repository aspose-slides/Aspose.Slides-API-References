---
title: MulticastDelegate()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří prázdnou kolekci.
type: docs
weight: 1
url: /cs/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() metoda

Vytvoří prázdnou kolekci.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) metoda

Ekvivalentní výchozímu konstruktoru.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) metoda

Provede mělkou kopii kolekce delegátů.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| o | const MulticastDelegate\& | Instance třídy MulticastDelegate, ze které se kopíruje kolekce delegátů. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) metoda

Konstruktor přesunu.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| o | MulticastDelegate\&& | Instance třídy MulticastDelegate, ze které se přesouvá kolekce delegátů. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) metoda

Vytvoří instanci a vloží zadaný delegát do kolekce delegátů.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | Delegát, který se vloží do kolekce delegátů |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) metoda

Vytvoří instanci a vloží zadanou hodnotu do kolekce delegátů.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ hodnoty, která se vloží do kolekce delegátů nově vytvořené instance; typ musí být převoditelný na typ Callback. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arg | T | Hodnota, která se vloží do kolekce delegátů |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) metoda

Vytvoří instanci a vloží zadanou hodnotu do kolekce delegátů.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Hodnota, která se vloží do kolekce delegátů |

## Viz také

* Typedef [Callback](../callback/)
* Třída [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)