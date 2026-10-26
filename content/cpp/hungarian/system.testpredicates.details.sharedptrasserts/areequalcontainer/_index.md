---
title: AreEqualContainer()
second_title: Aspose.Slides for C++ API Referenciája
description: Két tárolót hasonlít össze az elemeken az operator == használatával. Nem SmartPtr elemekkel működik.
type: docs
weight: 1
url: /hu/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1&, const T2&) függvény


Két tárolót hasonlít össze az elemeken az operator == használatával. Nem SmartPtr elemekkel működik.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS konténer típusa. |
| T2 | RHS konténer típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs | const T1& | LHS konténer. |
| rhs | const T2& | RHS konténer. |

### Visszatérési érték

True, ha a tárolt elemek és méretek egyeznek, false egyébként.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1&, const T2&) függvény


Két tárolót hasonlít össze az elemeken a [System::Object::Equals](../../system/object/equals/) használatával. [SmartPtr](../../system/smartptr/) elemekkel működik.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS konténer típusa. |
| T2 | RHS konténer típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs | const T1& | LHS konténer referencia. |
| rhs | const T2& | RHS konténer referencia. |

### Visszatérési érték

True, ha a tárolt elemek és méretek egyeznek, false egyébként.

## Lásd még

* Struktúra [IsSmartPtr](../../system/issmartptr/)
* Névtere [System::TestPredicates::Details::SharedPtrAsserts](../)
* Könyvtár [Aspose.Slides](../../)