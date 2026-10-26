---
title: MulticastDelegate()
second_title: Aspose.Slides for C++ API-referencia
description: Üres gyűjteményt hoz létre.
type: docs
weight: 1
url: /hu/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() metódus

Üres gyűjteményt hoz létre.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) metódus

Megegyezik az alapértelmezett konstruktorral.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) metódus

Végrehajt egy sekély másolatot a delegált gyűjteményről.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| o | const MulticastDelegate\& | Egy MulticastDelegate osztálypéldány, amelyből a delegáltak gyűjteményét másolni kell. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) metódus

Mozgató konstruktor.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| o | MulticastDelegate\&& | Egy MulticastDelegate osztálypéldány, amelyből a delegáltak gyűjteményét át kell mozgatni. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) metódus

Létrehoz egy példányt, és a megadott delegáltat a delegáltak gyűjteményébe helyezi.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | Egy delegált, amelyet a delegáltak gyűjteményébe kell helyezni. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) metódus

Létrehoz egy példányt, és a megadott értéket a delegáltak gyűjteményébe helyezi.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az újonnan létrehozott példány delegált gyűjteményébe elhelyezendő érték típusa; a típusnak konvertálhatónak kell lennie a Callback típusra. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arg | T | Egy érték, amelyet a delegáltak gyűjteményébe kell helyezni. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) metódus

Létrehoz egy példányt, és a megadott értéket a delegáltak gyűjteményébe helyezi.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Egy érték, amelyet a delegáltak gyűjteményébe kell helyezni. |

## Lásd még

* Typedef [Callback](../callback/)
* Osztály [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)