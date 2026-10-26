---
title: AreEqualContainer()
second_title: Aspose.Slides für C++ API Referenz
description: Vergleicht zwei Container elementweise mit dem Operator ==. Funktioniert für nicht-SmartPtr-Elemente.
type: docs
weight: 1
url: /de/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) Funktion


Vergleicht zwei Container elementweise mit operator ==. Funktioniert für nicht-SmartPtr-Elemente.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T1 | LHS-Container-Typ. |
| T2 | RHS-Container-Typ. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | LHS-Container. |
| rhs | const T2\& | RHS-Container. |

### Rückgabewert

True, wenn enthaltene Elemente und Größen übereinstimmen, false sonst.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) Funktion


Vergleicht zwei Container elementweise mit [System::Object::Equals](../../system/object/equals/). Funktioniert für [SmartPtr](../../system/smartptr/)-Elemente.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T1 | LHS-Container-Typ. |
| T2 | RHS-Container-Typ. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | LHS-Container-Referenz. |
| rhs | const T2\& | RHS-Container-Referenz. |

### Rückgabewert

True, wenn enthaltene Elemente und Größen übereinstimmen, false sonst.

## Siehe auch

* Struktur [IsSmartPtr](../../system/issmartptr/)
* Namensraum [System::TestPredicates::Details::SharedPtrAsserts](../)
* Bibliothek [Aspose.Slides](../../)