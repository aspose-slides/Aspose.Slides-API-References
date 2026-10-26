---
title: AreEqualData()
second_title: Aspose.Slides for C++ API Referencia
description: "Egyenlőség szerint hasonlítja össze a két tárolót a System::Object::Equals használatával az elemeknél. SmartPtr elemek esetén működik."
type: docs
weight: 14
url: /hu/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) függvény

Az elemeken [System::Object::Equals](../../system/object/equals/) használatával egyenlőség szerint hasonlítja össze a két tárolót. [SmartPtr](../../system/smartptr/) elemek esetén működik.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS container type. |
| T2 | RHS container type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs | const T1\& | LHS container reference. |
| rhs | const T2\& | RHS container reference. |

### Visszatérési érték

True, ha a tartalmazott elemek és méretek egyeznek, egyébként false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) függvény

Az elemeken az == operátor használatával egyenlőség szerint hasonlítja össze a két tárolót. Nem SmartPtr elemek esetén működik.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS container type. |
| T2 | RHS container type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs | const T1\& | LHS container. |
| rhs | const T2\& | RHS container. |

### Visszatérési érték

True, ha a tartalmazott elemek és méretek egyeznek, egyébként false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) függvény

Azonos típusú két tárolót egyenlőség szerint hasonlít össze. Nem SmartPtr elemek esetén működik.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS container type. |
| T2 | RHS container type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs | const T\& | LHS container. |
| rhs | const T\& | RHS container. |

### Visszatérési érték

True, ha a tartalmazott elemek és méretek egyeznek, egyébként false.

## Lásd még

* Struct [IsSmartPtr](../../system/issmartptr/)
* Névtér [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)