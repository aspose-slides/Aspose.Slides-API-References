---
title: Delegate()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Výchozí konstruktor. Vytvoří objekt delegáta, který neukazuje na nic.
type: docs
weight: 1
url: /cs/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() metoda

Výchozí konstruktor. Vytvoří objekt delegáta, který neukazuje na nic.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) metoda



```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) metoda

Přesunovací kopírovací konstruktor. Převádí vlastnictví entity, na kterou ukazuje zadaný delegát.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| o | Delegate\&& | Objekt Delegate, ze kterého se má přesunout ukazovaná entita |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) metoda

Konstruktor. Vytvoří objekt delegáta ze zadaného ukazatele na volnou funkci nebo statickou metodu.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| The | typ ukazatele na funkci nebo statickou metodu, který konstruktor přijímá jako argument |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| function | T | Ukazatel na funkci nebo statickou metodu, na kterou bude ukazovat nově vytvořený objekt Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) metoda

Konstruktor. Vytvoří delegáta ze zadaného ukazatele na funkční objekt vygenerovaný pomocí std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| The | typ funkčního objektu vygenerovaného pomocí std::bind(), který konstruktor přijímá jako argument |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| function | T | Ukazatel na "bind expression" - funkční ukazatel vygenerovaný pomocí std::bind() - na který bude ukazovat nově vytvořený objekt Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) metoda

Konstruktor. Vytvoří delegáta ze zadaného funkčního objektu.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | typ funkčního objektu, který konstruktor přijímá jako argument |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| functor_tag | int | Fiktivní celočíselná hodnota; tento argument se používá k vyřešení nejednoznačnosti |
| functor | T\& | Funkční objekt, na který nově vytvořený delegát bude ukazovat |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) metoda

Přesunovací konstruktor. Vytvoří delegáta ze zadaného funkčního objektu.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | typ funkčního objektu, který konstruktor přijímá jako argument |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| functor_tag | long | Fiktivní celočíselná hodnota; tento argument se používá k vyřešení nejednoznačnosti |
| functor | T\&& | Funkční objekt, na který nově vytvořený delegát bude ukazovat |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) metoda

Konstruktor. Vytvoří delegáta, který ukazuje na zadanou nestatickou metodu zadaného objektu.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| MemberType | typ nestatické metody, kterou konstruktor přijímá jako argument |
| ClassType | typ objektu, který konstruktor přijímá jako argument |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| member | MemberType ClassType::* | ukazatel na nestatickou metodu, na kterou bude nově vytvořený delegát ukazovat |
| obj | ClassType * | ukazatel na objekt, jehož metoda člena bude cílem nově vytvořeného delegáta |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) metoda

Konstruktor. Vytvoří delegáta, který ukazuje na zadanou nestatickou metodu zadaného objektu.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| MemberType | typ nestatické metody, kterou konstruktor přijímá jako argument |
| ClassType | typ objektu, který konstruktor přijímá jako argument |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| member | MemberType MemberClass::* | ukazatel na nestatickou metodu, na kterou bude nově vytvořený delegát ukazovat |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | sdílený ukazatel na objekt, jehož metoda člena bude cílem nově vytvořeného delegáta |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) metoda

Vytvoří objekt delegáta, který ukazuje na objekt funkce std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| R | návratový typ funkčního objektu, který konstruktor přijímá jako argument |
| Args | seznam argumentů funkčního objektu, který konstruktor přijímá jako argument |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| f | std::function\<R(Args...)> | funkční objekt, na který bude ukazovat nově vytvořený objekt delegáta |

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [Delegate< ReturnType(ArgumentTypes...)>](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)