---
title: AreEqualData()
second_title: Aspose.Slides voor C++ API Referentie
description: "Vergelijkt twee containers met System::Object::Equals op elementen. Werkt voor SmartPtr elementen."
type: docs
weight: 14
url: /nl/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function


Vergelijkt twee containers met [System::Object::Equals](../../system/object/equals/) op elementen. Werkt voor [SmartPtr](../../system/smartptr/) elementen.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T1 | LHS containertype. |
| T2 | RHS containertype. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | LHS containerreferentie. |
| rhs | const T2\& | RHS containerreferentie. |

### Retourwaarde

Waar als de elementen en groottes overeenkomen, onwaar anders.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function


Vergelijkt twee containers met operator == op elementen. Werkt voor niet-SmartPtr elementen.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T1 | LHS containertype. |
| T2 | RHS containertype. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | LHS container. |
| rhs | const T2\& | RHS container. |

### Retourwaarde

Waar als de elementen en groottes overeenkomen, onwaar anders.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) function


Vergelijkt twee containers van identiek type. Werkt voor niet-SmartPtr elementen.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T1 | LHS containertype. |
| T2 | RHS containertype. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T\& | LHS container. |
| rhs | const T\& | RHS container. |

### Retourwaarde

Waar als de elementen en groottes overeenkomen, onwaar anders.

## Zie ook

* Struct [IsSmartPtr](../../system/issmartptr/)
* Naamruimte [System::TestPredicates::Details::SharedPtrAsserts](../)
* Bibliotheek [Aspose.Slides](../../)