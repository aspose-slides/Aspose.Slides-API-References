---
title: AreEqualContainer()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Porównuje dwa kontenery przy użyciu operatora == na elementach. Działa dla nie-SmartPtr elementów.
type: docs
weight: 1
url: /pl/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) funkcja

Porównuje dwa kontenery przy użyciu operatora == na elementach. Działa dla elementów nie-SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ kontenera po lewej stronie. |
| T2 | Typ kontenera po prawej stronie. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs | const T1\& | Kontener po lewej stronie. |
| rhs | const T2\& | Kontener po prawej stronie. |

### Wartość zwracana

True, jeśli elementy i rozmiary się zgadzają, false w przeciwnym razie.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) funkcja

Porównuje dwa kontenery przy użyciu [System::Object::Equals](../../system/object/equals/) na elementach. Działa dla elementów [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ kontenera po lewej stronie. |
| T2 | Typ kontenera po prawej stronie. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs | const T1\& | Referencja do kontenera po lewej stronie. |
| rhs | const T2\& | Referencja do kontenera po prawej stronie. |

### Wartość zwracana

True, jeśli elementy i rozmiary się zgadzają, false w przeciwnym razie.

## Zobacz także

* Struktura [IsSmartPtr](../../system/issmartptr/)
* Przestrzeń nazw [System::TestPredicates::Details::SharedPtrAsserts](../)
* Biblioteka [Aspose.Slides](../../)