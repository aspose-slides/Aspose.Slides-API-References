---
title: AreEqualContainer()
second_title: Aspose.Slides för C++ API-referens
description: Jämför lika två behållare med operator == på elementen. Fungerar för icke-SmartPtr-element.
type: docs
weight: 1
url: /sv/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) funktion

Jämför lika två behållare med operator == på elementen. Fungerar för icke-SmartPtr-element.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS behållartyp. |
| T2 | RHS behållartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | const T1\& | LHS behållare. |
| rhs | const T2\& | RHS behållare. |

### Returvärde

Sant om innehållna element och storlekar matchar, falskt annars.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) funktion

Jämför lika två behållare med [System::Object::Equals](../../system/object/equals/) på elementen. Fungerar för [SmartPtr](../../system/smartptr/) element.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS behållartyp. |
| T2 | RHS behållartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | const T1\& | LHS behållarreferens. |
| rhs | const T2\& | RHS behållarreferens. |

### Returvärde

Sant om innehållna element och storlekar matchar, falskt annars.

## Se även

* Struktur [IsSmartPtr](../../system/issmartptr/)
* Namnrymd [System::TestPredicates::Details::SharedPtrAsserts](../)
* Bibliotek [Aspose.Slides](../../)