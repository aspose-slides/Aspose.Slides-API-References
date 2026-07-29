---
title: AreEqualData()
second_title: Aspose.Slides för C++ API-referens
description: "Jämför två containrar med System::Object::Equals på element. Fungerar för SmartPtr-element."
type: docs
weight: 14
url: /sv/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) funktion

Jämför två containrar med [System::Object::Equals](../../system/object/equals/) på element. Fungerar för [SmartPtr](../../system/smartptr/) element.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
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

Sant om de innehållna elementen och storlekarna matchar, falskt annars.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) funktion

Jämför två containrar med operator == på element. Fungerar för icke-SmartPtr-element.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
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

Sant om de innehållna elementen och storlekarna matchar, falskt annars.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) funktion

Jämför två containrar av identisk typ. Fungerar för icke-SmartPtr-element.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS behållartyp. |
| T2 | RHS behållartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | const T\& | LHS behållare. |
| rhs | const T\& | RHS behållare. |

### Returvärde

Sant om de innehållna elementen och storlekarna matchar, falskt annars.

## Se också

* Struktur [IsSmartPtr](../../system/issmartptr/)
* Namnrymd [System::TestPredicates::Details::SharedPtrAsserts](../)
* Bibliotek [Aspose.Slides](../../)