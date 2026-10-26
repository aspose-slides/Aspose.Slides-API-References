---
title: AreEqualContainer()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare en égalité deux conteneurs en utilisant l'opérateur == sur les éléments. Fonctionne pour les éléments non-SmartPtr.
type: docs
weight: 1
url: /fr/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) fonction

Compare en égalité deux conteneurs en utilisant operator == sur les éléments. Fonctionne pour les éléments non-SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T1 | Type de conteneur LHS. |
| T2 | Type de conteneur RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | Conteneur LHS. |
| rhs | const T2\& | Conteneur RHS. |

### Valeur de retour

True si les éléments contenus et les tailles correspondent, false sinon.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) fonction

Compare en égalité deux conteneurs en utilisant [System::Object::Equals](../../system/object/equals/) sur les éléments. Fonctionne pour les éléments [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T1 | Type de conteneur LHS. |
| T2 | Type de conteneur RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | Référence du conteneur LHS. |
| rhs | const T2\& | Référence du conteneur RHS. |

### Valeur de retour

True si les éléments contenus et les tailles correspondent, false sinon.

## See Also

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)