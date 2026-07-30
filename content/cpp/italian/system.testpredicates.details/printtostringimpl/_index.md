---
title: PrintToStringImpl()
second_title: Riferimento API di Aspose.Slides per C++
description: "Stampa la sottoclasse System::Object in stringa usando il metodo ToString()."
type: docs
weight: 14
url: /it/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) funzione


Stampa la sottoclasse [System::Object](../../system/object/) in stringa usando il metodo ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```


### Parametri template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo della classe finale. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Puntatore all'oggetto da stampare. |
| s | long long | Un parametro di servizio che funge da selettore di overload della funzione in base al tipo di questo parametro; il valore del parametro è ignorato |

### Valore restituito

[String](../../system/string/) rappresentazione dell'oggetto passato o \"nullptr\", se **value** è nullo.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) funzione


Stampa la sottoclasse [System::Object](../../system/object/) in stringa usando il metodo ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```


### Parametri template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo della classe finale. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Puntatore all'oggetto da stampare. |
| s | long long | Un parametro di servizio che funge da selettore di overload della funzione in base al tipo di questo parametro; il valore del parametro è ignorato |

### Valore restituito

[String](../../system/string/) rappresentazione dell'oggetto passato o \"nullptr\", se **value** è nullo.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) funzione


Stampa l'oggetto in stringa usando il metodo ToString().

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parametri template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) da stampare. |
| s | long long | Un parametro di servizio che funge da selettore di overload della funzione in base al tipo di questo parametro; il valore del parametro è ignorato |

### Valore restituito

[String](../../system/string/) rappresentazione dell'oggetto passato.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) funzione


Stampa l'oggetto in stringa usando il metodo PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parametri template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) da stampare. |
| s | long long | Un parametro di servizio che funge da selettore di overload della funzione in base al tipo di questo parametro; il valore del parametro è ignorato |

### Valore restituito

[String](../../system/string/) rappresentazione dell'oggetto passato.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) funzione


Stampa l'oggetto in stringa usando il metodo PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parametri template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) da stampare. |
| s | long long | Un parametro di servizio che funge da selettore di overload della funzione in base al tipo di questo parametro; il valore del parametro è ignorato |

### Valore restituito

[String](../../system/string/) rappresentazione dell'oggetto passato.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) funzione


Stampa la coppia in stringa.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```


### Parametri template

| Parametro | Descrizione |
| --- | --- |
| T1 | Primo tipo di argomento della coppia. |
| T2 | Secondo tipo di argomento della coppia. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) da stampare. |
| s | long long | Un parametro di servizio che funge da selettore di overload della funzione in base al tipo di questo parametro; il valore del parametro è ignorato |

### Valore restituito

Rappresentazioni stringa congiunte di entrambe le componenti prima e seconda della coppia.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) funzione


Stampa la coppia in stringa.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```


### Parametri template

| Parametro | Descrizione |
| --- | --- |
| T1 | Primo tipo di argomento della coppia. |
| T2 | Secondo tipo di argomento della coppia. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) da stampare. |
| s | long long | Un parametro di servizio che funge da selettore di overload della funzione in base al tipo di questo parametro; il valore del parametro è ignorato |

### Valore restituito

Rappresentazioni stringa congiunte di entrambe le componenti prima e seconda della coppia.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) funzione


Stampa i contenitori in stile STL in stringa stampando i loro elementi (non più di 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```


### Parametri template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) da stampare. |
| s | long long | Un parametro di servizio che funge da selettore di overload della funzione in base al tipo di questo parametro; il valore del parametro è ignorato |

### Valore restituito

Rappresentazioni stringa congiunte degli elementi contenuti.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) funzione


Stampa altri tipi in stringa usando le funzioni fornite da gtest.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```


### Parametri template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) da stampare. |
| s | int | Un parametro di servizio che funge da selettore di overload della funzione in base al tipo di questo parametro; il valore del parametro è ignorato |

### Valore restituito

[String](../../system/string/) rappresentazioni dell'oggetto passato.

## Vedi anche

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [WeakPtr](../../system/weakptr/)
* Classe [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Classe [Object](../../system/object/)
* Struct [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struct [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)