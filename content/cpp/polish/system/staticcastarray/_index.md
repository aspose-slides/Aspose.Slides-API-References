---
title: StaticCastArray()
second_title: Aspose.Slides dla C++ – Odniesienie API
description: Wykonuje rzutowanie elementów określonej tablicy na inny typ. Nadpisanie w przypadkach, gdy From jest obiektem SmartPtr.
type: docs
weight: 2978
url: /pl/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) funkcja


Performs casting of elements of the specified array to different type. Override for cases then From is [SmartPtr](../smartptr/) obj.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| To | The type to cast the elements of the specified array to |
| From | The type of elements of the elements of the arry elements of which to cast |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Shared pointer to the array containing the elements to cast |

### Wartość zwracana

A pointer to a new array containing elements of type **To** equivalent to the elements of **from**

Przestarzałe
:   Added for backward compatibility. Use ExplicitCast instead.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) funkcja


Performs casting of elements of the specified array to different type. Override for cases then From is Boxable and To is [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| To | The type to cast the elements of the specified array to |
| From | The type of elements of the elements of the arry elements of which to cast |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Shared pointer to the array containing the elements to cast |

### Wartość zwracana

A pointer to a new array containing elements of type **To** equivalent to the elements of **from**

Przestarzałe
:   Added for backward compatibility. Use ExplicitCast instead.

## Zobacz także

* Typedef [SharedPtr](../sharedptr/)
* Klasa [Array](../array/)
* Klasa [Object](../object/)
* Struktura [IsSmartPtr](../issmartptr/)
* Struktura [IsBoxable](../isboxable/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)