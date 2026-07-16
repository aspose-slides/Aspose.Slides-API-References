---
title: ISensitivityLabel
second_title: Aspose.Slides pour C++ Référence de l'API
description: Représente le libellé de sensibilité de Microsoft Purview Information Protection.
type: docs
weight: 3615
url: /fr/aspose.slides/isensitivitylabel/
---
## ISensitivityLabel classe

Représente le libellé de sensibilité de Microsoft Purview Information Protection.

```cpp
class ISensitivityLabel : public virtual System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux bien que selon IEC 60559:1989 le NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux bien que selon IEC 60559:1989 le NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual [SensitivityLabelAssignmentType](../sensitivitylabelassignmenttype/) [get_AssignmentMethodType](./get_assignmentmethodtype/)() | Renvoie la méthode d'affectation pour le libellé de sensibilité. Lire [SensitivityLabelAssignmentType](../sensitivitylabelassignmenttype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SensitivityLabelContentType](../sensitivitylabelcontenttype/)\>\> [get_ContentMarkTypes](./get_contentmarktypes/)() | Renvoie la liste des types de marquage de contenu qui doivent être appliqués à un fichier. |
| virtual [System::String](../../system/string/) [get_Id](./get_id/)() | Renvoie l'identifiant du libellé de sensibilité. Lire [System::String](../../system/string/). |
| virtual **bool** [get_IsEnabled](./get_isenabled/)() | Indique si le libellé de sensibilité est activé. |
| virtual **bool** [get_IsRemoved](./get_isremoved/)() | Indique si le libellé de sensibilité a été supprimé. |
| virtual [System::Guid](../../system/guid/) [get_SiteId](./get_siteid/)() | Renvoie l'identifiant du site Azure Active Directory (Azure AD) correspondant à la politique du libellé de sensibilité qui décrit le libellé de sensibilité. Lire [System::Guid](../../system/guid/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogique de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Active le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogique de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogique de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogique de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Active le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie en réalité rien, il initialise simplement un nouvel objet et permet la copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie en réalité rien, il initialise simplement un nouvel objet et permet la copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [set_AssignmentMethodType](./set_assignmentmethodtype/)([SensitivityLabelAssignmentType](../sensitivitylabelassignmenttype/)) | Définit la méthode d'affectation pour le libellé de sensibilité. Écrire [SensitivityLabelAssignmentType](../sensitivitylabelassignmenttype/). |
| virtual void [set_Id](./set_id/)([System::String](../../system/string/)) | Définit l'identifiant du libellé de sensibilité. Écrire [System::String](../../system/string/). |
| virtual void [set_IsEnabled](./set_isenabled/)(**bool**) | Indique si le libellé de sensibilité est activé. |
| virtual void [set_IsRemoved](./set_isremoved/)(**bool**) | Indique si le libellé de sensibilité a été supprimé. |
| virtual void [set_SiteId](./set_siteid/)([System::Guid](../../system/guid/)) | Définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la politique du libellé de sensibilité qui décrit le libellé de sensibilité. Écrire [System::Guid](../../system/guid/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nième argument du modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogique de la méthode C# [Object.ToString()](../../system/object/tostring/). Active la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)