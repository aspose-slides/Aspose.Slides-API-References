---
title: connect()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Dodaje określony delegat do kolekcji.
type: docs
weight: 144
url: /pl/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) metoda


Dodaje określony delegat do kolekcji.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| callback | [Callback](../callback/) | Delegat do dodania do kolekcji |

### Wartość zwracana

Referencja do siebie

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) metoda


Dodaje określony obiekt funkcyjny do kolekcji delegatów. Obiekt funkcyjny jest konwertowany na typ delegata Callback przed dodaniem do kolekcji.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| R | Typ zwracany obiektu funkcyjnego, który ma być dodany do kolekcji |
| Args | Lista argumentów obiektu funkcyjnego, który ma być dodany do kolekcji |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Obiekt funkcyjny do dodania do kolekcji |

### Wartość zwracana

Referencja do siebie

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) metoda


Dodaje określony obiekt MulticastDelegate do kolekcji delegatów.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Instancja klasy MulticastDelegate do dodania do kolekcji delegatów |

### Wartość zwracana

Referencja do siebie

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) metoda


Dodaje określoną metodę niestatyczną wskazanego obiektu do kolekcji delegatów.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| MemberType | Typ metody niestatycznej, która ma zostać dodana do kolekcji delegatów |
| ClassType | Typ obiektu, którego metoda ma zostać dodana do delegata |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| member | MemberType ClassType::* | Wskaźnik na metodę niestatyczną wskazanego obiektu |
| obj | ClassType * | Wskaźnik na metodę składową obiektu, która ma zostać dodana do kolekcji delegatów |

### Wartość zwracana

Referencja do siebie

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) metoda


Dodaje określoną metodę niestatyczną wskazanego obiektu do kolekcji delegatów.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| MemberType | Typ metody niestatycznej, która ma zostać dodana do kolekcji delegatów |
| ClassType | Typ obiektu, którego metoda ma zostać dodana do kolekcji delegatów |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| member | MemberType ClassType::* | Wskaźnik na metodę niestatyczną wskazanego obiektu |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Wspólny wskaźnik (SharedPtr) do metody składowej obiektu, która ma zostać dodana do kolekcji delegatów |

### Wartość zwracana

Referencja do siebie

## Zobacz także

* Definicja typu [Callback](../callback/)
* Definicja typu [SharedPtr](../../sharedptr/)
* Metoda [MulticastDelegate](../multicastdelegate/)
* Klasa [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)