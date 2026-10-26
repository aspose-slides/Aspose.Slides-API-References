---
title: Delegate()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konstruktor domyślny. Tworzy obiekt delegata, który nie wskazuje na nic.
type: docs
weight: 1
url: /pl/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() metoda

Domyślny konstruktor. Tworzy obiekt delegata, który nie wskazuje na nic.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) metoda




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) metoda

Konstruktor kopiujący przenoszący. Przejmuje własność jednostki wskazywanej przez określony delegat.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| o | Delegate\&& | Obiekt Delegate, z którego zostanie przeniesiona wskazywana jednostka |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) metoda

Konstruktor. Tworzy obiekt delegata z podanego wskaźnika do wolnej funkcji lub metody statycznej.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| The | typ wskaźnika do funkcji lub metody statycznej akceptowanego przez konstruktor jako argument |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| function | T | Wskaźnik do funkcji lub metody statycznej, na którą będzie wskazywała nowo utworzona instancja Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) metoda

Konstruktor. Tworzy delegata z podanego wskaźnika do obiektu funkcyjnego wygenerowanego przez std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| The | typ obiektu funkcyjnego wygenerowanego przez std::bind() akceptowanego przez konstruktor jako argument |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| function | T | Wskaźnik do \"bind expression\" - wskaźnika do funkcji wygenerowanego przez std::bind() - na który będzie wskazywała nowo utworzona instancja Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) metoda

Konstruktor. Tworzy delegata z podanego obiektu funkcyjnego.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ obiektu funkcyjnego akceptowanego przez konstruktor jako argument |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functor_tag | int | Sztuczna wartość całkowita; ten argument jest używany do rozwiązywania niejednoznaczności |
| functor | T\& | Obiekt funkcyjny, na który nowo utworzony delegat będzie wskazywał |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) metoda

Konstruktor przenoszący. Tworzy delegata z podanego obiektu funkcyjnego.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ obiektu funkcyjnego akceptowanego przez konstruktor jako argument |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functor_tag | long | Sztuczna wartość całkowita; ten argument jest używany do rozwiązywania niejednoznaczności |
| functor | T\&& | Obiekt funkcyjny, na który nowo utworzony delegat będzie wskazywał |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) metoda

Konstruktor. Tworzy delegata, który wskazuje określoną metodę niestatyczną podanego obiektu.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| MemberType | typ metody niestatycznej akceptowanej przez konstruktor jako argument |
| ClassType | typ obiektu akceptowanego przez konstruktor jako argument |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| member | MemberType ClassType::* | Wskaźnik do metody niestatycznej, na którą będzie wskazywał nowo utworzony delegat |
| obj | ClassType * | Wskaźnik do obiektu, którego metoda członkowska będzie wskazywana przez nowo utworzony delegat |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) metoda

Konstruktor. Tworzy delegata, który wskazuje określoną metodę niestatyczną podanego obiektu.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| MemberType | typ metody niestatycznej akceptowanej przez konstruktor jako argument |
| ClassType | typ obiektu akceptowanego przez konstruktor jako argument |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| member | MemberType MemberClass::* | Wskaźnik do metody niestatycznej, na którą będzie wskazywał nowo utworzony delegat |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Wskaźnik współdzielony do obiektu, którego metoda członkowska będzie wskazywana przez nowo utworzony delegat |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) metoda

Tworzy obiekt delegata, który wskazuje obiekt funkcji std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| R | typ zwracany obiektu funkcyjnego akceptowanego przez konstruktor jako argument |
| Args | lista argumentów obiektu funkcyjnego akceptowanego przez konstruktor jako argument |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Obiekt funkcyjny, na który będzie wskazywał nowo utworzony obiekt delegata |

## Zobacz też

* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [Delegate< ReturnType(ArgumentTypes...)>](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)