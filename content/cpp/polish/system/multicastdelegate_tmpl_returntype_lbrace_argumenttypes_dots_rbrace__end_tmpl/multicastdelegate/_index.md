---
title: MulticastDelegate()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy pustą kolekcję.
type: docs
weight: 1
url: /pl/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() metoda

Tworzy pustą kolekcję.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) metoda

Odpowiednik domyślnego konstruktora.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) metoda

Wykonuje płytką kopię kolekcji delegatów.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| o | const MulticastDelegate\& | Instancja klasy MulticastDelegate, z której kopiowana jest kolekcja delegatów. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) metoda

Konstruktor przenoszący.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| o | MulticastDelegate\&& | Instancja klasy MulticastDelegate, z której przenoszona jest kolekcja delegatów. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) metoda

Tworzy instancję i umieszcza określony delegat w kolekcji delegatów.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | Delegat do umieszczenia w kolekcji delegatów |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) metoda

Tworzy instancję i umieszcza określoną wartość w kolekcji delegatów.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartości, którą należy umieścić w kolekcji delegatów nowo utworzonej instancji; typ musi być konwertowalny na typ Callback. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arg | T | Wartość do umieszczenia w kolekcji delegatów |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) metoda

Tworzy instancję i umieszcza określoną wartość w kolekcji delegatów.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Wartość do umieszczenia w kolekcji delegatów |

## Zobacz także

* Definicja typu [Callback](../callback/)
* Klasa [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)