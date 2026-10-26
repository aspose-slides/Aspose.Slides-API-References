---
title: ECCurve
second_title: Référence de l'API Aspose.Slides pour C++
description: Une courbe elliptique.
type: docs
weight: 716
url: /fr/system.security.cryptography/eccurve/
---
## ECCurve struct

Une courbe elliptique.

```cpp
class ECCurve
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Crée une courbe à partir du nom convivial OID spécifié. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Crée une courbe à partir de l'oid spécifié. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Crée une courbe à partir de la valeur OID spécifiée. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Obtient [Oid](../oid/) représentant la courbe nommée. |
| void [Validate](./validate/)() const | Valide la courbe actuelle. |

## Énumérations

| Énum | Description |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Type de courbe elliptique. |

## Voir aussi

* Espace de noms [System::Security::Cryptography](../)
* Bibliothèque [Aspose.Slides](../../)