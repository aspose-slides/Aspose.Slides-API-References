---
title: Is()
second_title: Riferimento API di Aspose.Slides per C++
description: Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi boxable (value) che sono esattamente quelli.
type: docs
weight: 92
url: /it/system/objectext/is/
---
## ObjectExt::Is(const T\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi boxable (value) che sono esattamente quelli.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) per testare l'operatore 'is'. Ignorato. |

### Valore restituito

Sempre true

## ObjectExt::Is(const U\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi puntatore ottimizzata per classi 'final'.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |
| U | Tipo testato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) per testare l'operatore 'is'. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(const U\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi puntatore.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |
| U | Tipo testato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) per testare l'operatore 'is'. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(const Object\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi valore.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) per testare l'operatore 'is'. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(const Object\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi non convertibili.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) per testare l'operatore 'is'. |

### Valore restituito

Sempre false poiché i tipi non sono convertibili.

## ObjectExt::Is(const SmartPtr\<U\>\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi puntatore.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) per testare l'operatore 'is'. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi wrapper di eccezione.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) per testare l'operatore 'is'. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi nullable.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) per testare l'operatore 'is'. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi boxable con operatore == definito.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) per testare l'operatore 'is'. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi boxable senza operatore == definito.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) per testare l'operatore 'is'. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(const SmartPtr\<V\>\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi valore incapsulati in interfacce.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |
| V | Tipo dell'oggetto puntato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) per testare l'operatore 'is'. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(const SmartPtr\<U\>\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi enum.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |
| U | Tipo dell'oggetto puntato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) per testare l'operatore 'is'. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(const WeakPtr\<U\>\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi enum rispetto a puntatori deboli.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |
| U | Tipo dell'oggetto puntato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) per testare l'operatore 'is'. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(const Nullable\<U\>\&) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per tipo [Nullable](../../nullable/).

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) tipo. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(const char16_t *) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per letterale stringa.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) letterale. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## ObjectExt::Is(int32_t) metodo


Implementa la traduzione dell'operatore 'is'. Specializzazione per letterale intero.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **int32_t** | letterale intero. |

### Valore restituito

True se 'is' restituisce true, false altrimenti.

## Vedi anche

* Class [ObjectExt](../)
* Class [Object](../../object/)
* Class [SmartPtr](../../smartptr/)
* Class [ExceptionWrapper](../../exceptionwrapper/)
* Class [WeakPtr](../../weakptr/)
* Class [Nullable](../../nullable/)
* Struct [IsBoxable](../../isboxable/)
* Struct [IsSmartPtr](../../issmartptr/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)