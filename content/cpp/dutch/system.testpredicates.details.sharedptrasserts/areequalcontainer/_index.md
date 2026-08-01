---
title: AreEqualContainer()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt twee containers met operator == op elementen. Werkt voor niet-SmartPtr elementen.
type: docs
weight: 1
url: /nl/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) functie


Vergelijkt twee containers met operator == op elementen. Werkt voor niet-SmartPtr elementen.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS containertype. |
| T2 | RHS containertype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | const T1\& | LHS container. |
| rhs | const T2\& | RHS container. |

### Retourwaarde

True als de elementen en groottes overeenkomen, false anders.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) functie


Vergelijkt twee containers met [System::Object::Equals](../../system/object/equals/) op elementen. Werkt voor [SmartPtr](../../system/smartptr/) elementen.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS containertype. |
| T2 | RHS containertype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | const T1\& | LHS containerreferentie. |
| rhs | const T2\& | RHS containerreferentie. |

### Retourwaarde

True als de elementen en groottes overeenkomen, false anders.

## Zie ook

* Struct [IsSmartPtr](../../system/issmartptr/)
* Naamruimte [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)