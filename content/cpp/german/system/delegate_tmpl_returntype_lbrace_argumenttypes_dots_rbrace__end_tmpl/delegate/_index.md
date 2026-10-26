---
title: Delegate()
second_title: Aspose.Slides für C++ API-Referenz
description: Standardkonstruktor. Erstellt das Delegatenobjekt, das auf nichts zeigt.
type: docs
weight: 1
url: /de/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() Methode

Default-Konstruktor. Erstellt das Delegatenobjekt, das auf nichts zeigt.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) Methode

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) Methode

Verschiebender Kopierkonstruktor. Übernimmt den Besitz einer Entität, auf die der angegebene Delegat zeigt.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | Delegate\&& | Das Delegate-Objekt, von dem die referenzierte Entität verschoben wird |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) Methode

Konstruktor. Erstellt ein Delegatenobjekt aus dem angegebenen Zeiger auf eine freie Funktion oder statische Methode.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| The | Der Typ des Funktions- oder Methodenzeigers, der vom Konstruktor als Argument akzeptiert wird |

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| function | T | Zeiger auf eine Funktion oder eine statische Methode, auf die das neu erstellte Delegate-Instanz zeigen wird |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) Methode

Konstruktor. Erstellt ein Delegat aus dem angegebenen Zeiger auf das Funktionsobjekt, das von std::bind() erzeugt wurde.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| The | Der Typ des Funktionsobjekts, das von std::bind() erzeugt wurde und vom Konstruktor als Argument akzeptiert wird |

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| function | T | Zeiger auf einen \"bind expression\" - ein Funktionszeiger, der von std::bind() erzeugt wurde - auf den das neu erstellte Delegate-Instanz zeigen wird |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) Methode

Konstruktor. Erstellt ein Delegat aus dem angegebenen Funktionsobjekt.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Funktionsobjekts, das vom Konstruktor als Argument akzeptiert wird |

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functor_tag | int | Ein Dummy-Ganzzahlwert; dieses Argument wird verwendet, um Mehrdeutigkeiten zu lösen |
| functor | T\& | Ein Funktionsobjekt, auf das das neu konstruierte Delegat zeigen wird |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) Methode

Verschiebender Konstruktor. Erstellt ein Delegat aus dem angegebenen Funktionsobjekt.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Funktionsobjekts, das vom Konstruktor als Argument akzeptiert wird |

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functor_tag | long | Ein Dummy-Ganzzahlwert; dieses Argument wird verwendet, um Mehrdeutigkeiten zu lösen |
| functor | T\&& | Ein Funktionsobjekt, auf das das neu konstruierte Delegat zeigen wird |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) Methode

Konstruktor. Erstellt ein Delegat, das auf die angegebene nicht-statische Methode des angegebenen Objekts zeigt.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| MemberType | Der Typ der nicht-statischen Methode, die der Konstruktor als Argument akzeptiert |
| ClassType | Der Typ des Objekts, das der Konstruktor als Argument akzeptiert |

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| member | MemberType ClassType::* | Ein Zeiger auf die nicht-statische Methode, auf die das neu erstellte Delegat zeigen wird |
| obj | ClassType * | Ein Zeiger auf ein Objekt, dessen Mitgliedsmethode vom neu erstellten Delegat referenziert wird |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) Methode

Konstruktor. Erstellt ein Delegat, das auf die angegebene nicht-statische Methode des angegebenen Objekts zeigt.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| MemberType | Der Typ der nicht-statischen Methode, die der Konstruktor als Argument akzeptiert |
| ClassType | Der Typ des Objekts, das der Konstruktor als Argument akzeptiert |

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| member | MemberType MemberClass::* | Ein Zeiger auf die nicht-statische Methode, auf die das neu erstellte Delegat zeigen wird |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Ein SharedPtr auf ein Objekt, dessen Mitgliedsmethode vom neu erstellten Delegat referenziert wird |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) Methode

Erstellt ein Delegatenobjekt, das auf ein std::function-Funktionsobjekt zeigt.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| R | Der Rückgabetyp des Funktionsobjekts, das vom Konstruktor als Argument akzeptiert wird |
| Args | Die Argumentliste des Funktionsobjekts, das vom Konstruktor als Argument akzeptiert wird |

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Ein Funktionsobjekt, auf das das neu erstellte Delegatenobjekt zeigen wird |

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)