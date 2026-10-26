---
title: Delegate()
second_title: Aspose.Slides C++ API referencia
description: Alapértelmezett konstruktor. Létrehozza a delegate objektumot, amely nem mutat semmire.
type: docs
weight: 1
url: /hu/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() metódus

Alapértelmezett konstruktor. Létrehozza a delegate objektumot, amely nem mutat semmire.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) metódus




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) metódus

Mozgó másoló konstruktor. Átveszi a megadott delegate által mutatott entitás tulajdonjogát.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| o | Delegate\&& | A Delegate objektum, amelyből áthelyezi a mutatott entitást |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) metódus

Konstruktor. Létrehozza egy delegate objektumot a megadott szabad függvényre vagy statikus metódusra mutató pointerből.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| The | a függvény- vagy statikus metódus pointer típusa, amelyet a konstruktor argumentumként elfogad |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| function | T | Mutató egy függvényre vagy statikus metódusra, amelyre az újonnan létrehozott Delegate példány mutatni fog |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) metódus

Konstruktor. Létrehozza a delegate-et a megadott pointerből, amely a std::bind() által generált függvényobjektumra mutat.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| The | a std::bind() által generált függvényobjektum típusa, amelyet a konstruktor argumentumként elfogad |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| function | T | Mutató egy "bind kifejezésre" – egy függvény pointerre, amelyet a std::bind() generált – amelyre az újonnan létrehozott Delegate példány mutatni fog |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) metódus

Konstruktor. Létrehozza a delegate-et a megadott függvényobjektumból.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | a konstruktor által argumentumként elfogadott függvényobjektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functor_tag | int | Egy látszólagos egész érték; ez az argumentum a kettősség feloldására szolgál |
| functor | T\& | Egy függvényobjektum, amelyre az újonnan létrehozott delegate mutatni fog |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) metódus

Mozgó konstruktor. Létrehozza a delegate-et a megadott függvényobjektumból.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | a konstruktor által argumentumként elfogadott függvényobjektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functor_tag | long | Egy látszólagos egész érték; ez az argumentum a kettősség feloldására szolgál |
| functor | T\&& | Egy függvényobjektum, amelyre az újonnan létrehozott delegate mutatni fog |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) metódus

Konstruktor. Létrehozza a delegate-et, amely a megadott objektum nem statikus metódusára mutat.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| MemberType | A konstruktor által argumentumként elfogadott nem statikus metódus típusa |
| ClassType | A konstruktor által argumentumként elfogadott objektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| member | MemberType ClassType::* | Pointer a nem statikus metódusra, amelyre az újonnan létrehozott delegate mutatni fog |
| obj | ClassType * | Pointer egy objektum példányra, amelynek a tagmetódusára az újonnan létrehozott delegate mutatni fog |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) metódus

Konstruktor. Létrehozza a delegate-et, amely a megadott objektum nem statikus metódusára mutat.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| MemberType | A konstruktor által argumentumként elfogadott nem statikus metódus típusa |
| ClassType | A konstruktor által argumentumként elfogadott objektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| member | MemberType MemberClass::* | Pointer a nem statikus metódusra, amelyre az újonnan létrehozott delegate mutatni fog |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Egy megosztott pointer egy objektum tagmetódusára, amelyre az újonnan létrehozott delegate mutatni fog |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) metódus

Létrehoz egy delegate objektumot, amely egy std::function függvényobjektumra mutat.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| R | A függvényobjektum visszatérési típusa, amelyet a konstruktor argumentumként elfogad |
| Args | A függvényobjektum argumentumlistája, amelyet a konstruktor argumentumként elfogad |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Egy függvényobjektum, amelyre az újonnan létrehozott delegate objektum mutatni fog |

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [Delegate< ReturnType(ArgumentTypes...)>](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)