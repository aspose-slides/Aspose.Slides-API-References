---
title: AreEqualData()
second_title: Référence API Aspose.Slides pour C++
description: "Compare deux conteneurs en utilisant System::Object::Equals sur les éléments. Fonctionne pour les éléments SmartPtr."
type: docs
weight: 14
url: /fr/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) fonction

Compare deux conteneurs en utilisant [System::Object::Equals](../../system/object/equals/) sur les éléments. Fonctionne pour les éléments [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type de conteneur LHS. |
| T2 | Type de conteneur RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | Référence du conteneur LHS. |
| rhs | const T2\& | Référence du conteneur RHS. |

### Valeur de retour

Vrai si les éléments contenus et les tailles correspondent, faux sinon.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) fonction

Compare deux conteneurs en utilisant l'opérateur == sur les éléments. Fonctionne pour les éléments non-SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type de conteneur LHS. |
| T2 | Type de conteneur RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | Conteneur LHS. |
| rhs | const T2\& | Conteneur RHS. |

### Valeur de retour

Vrai si les éléments contenus et les tailles correspondent, faux sinon.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) fonction

Compare deux conteneurs du même type. Fonctionne pour les éléments non-SmartPtr.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type de conteneur LHS. |
| T2 | Type de conteneur RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | const T\& | Conteneur LHS. |
| rhs | const T\& | Conteneur RHS. |

### Valeur de retour

Vrai si les éléments contenus et les tailles correspondent, faux sinon.

## Voir aussi

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)