---
title: AreEqualData()
second_title: Aspose.Slides für C++ API-Referenz
description: "Vergleicht zwei Container mithilfe von System::Object::Equals auf Elemente. Funktioniert für SmartPtr-Elemente."
type: docs
weight: 14
url: /de/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1&, const T2&) Funktion


Vergleicht zwei Container mithilfe von [System::Object::Equals](../../system/object/equals/) auf Elemente. Funktioniert für [SmartPtr](../../system/smartptr/) Elemente.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Linker Containertyp. |
| T2 | Rechter Containertyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs | const T1& | Linker Container-Referenz. |
| rhs | const T2& | Rechter Container-Referenz. |

### Rückgabewert

True, wenn enthaltene Elemente und Größen übereinstimmen, sonst false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1&, const T2&) Funktion


Vergleicht zwei Container mithilfe des Operators == auf Elemente. Funktioniert für nicht-SmartPtr-Elemente.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Linker Containertyp. |
| T2 | Rechter Containertyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs | const T1& | Linker Container. |
| rhs | const T2& | Rechter Container. |

### Rückgabewert

True, wenn enthaltene Elemente und Größen übereinstimmen, sonst false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T&, const T&) Funktion


Vergleicht zwei Container des gleichen Typs. Funktioniert für nicht-SmartPtr-Elemente.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Linker Containertyp. |
| T2 | Rechter Containertyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs | const T& | Linker Container. |
| rhs | const T& | Rechter Container. |

### Rückgabewert

True, wenn enthaltene Elemente und Größen übereinstimmen, sonst false.

## Siehe auch

* Struktur [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Bibliothek [Aspose.Slides](../../)