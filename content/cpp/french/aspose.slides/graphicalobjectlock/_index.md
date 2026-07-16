---
title: GraphicalObjectLock
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine quelles opérations sont désactivées sur le parent GraphicalObject.
type: docs
weight: 1184
url: /fr/aspose.slides/graphicalobjectlock/
---
## GraphicalObjectLock classe

Détermine quelles opérations sont désactivées sur le parent [GraphicalObject](../graphicalobject/).

```cpp
class GraphicalObjectLock : public Aspose::Slides::BaseShapeLock,
                            public Aspose::Slides::IGraphicalObjectLock
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la semantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type reference dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emule la comparaison a virgule flottante de style C# où deux NaN sont consideres comme egaux meme si, selon IEC 60559:1989, NaN n'est egal a aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emule la comparaison a virgule flottante de style C# où deux NaN sont consideres comme egaux meme si, selon IEC 60559:1989, NaN n'est egal a aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | A usage interne uniquement. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Determine si la forme doit preserver le rapport d'aspect lors du redimensionnement. Lecture **bool**. |
| **bool** [get_DrilldownLocked](./get_drilldownlocked/)() override | Determine si la selection des sous-formes de cet objet est interdite. Lecture **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Determine si l'ajout de cette forme a un groupe est interdit. Lecture **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Renvoie true si tous les drapeaux de verrouillage sont desactiveS. Lecture seule **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Determine si le deplacement de cette forme est interdit. Lecture **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Determine si la selection de cette forme est interdite. Lecture **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Determine si le redimensionnement de cette forme est interdit. Lecture **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de donnees du compteur de references associee a l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la methode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalises. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type reel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifie si l'objet represente une instance du type décrit par targetType. Analogue de l'operateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Met en oeuvre le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la methode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalises. |
|  [Object](../../system/object/object/)() | Cree l'objet. Initialise toutes les structures de donnees internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie reellement rien, il initialise simplement un nouvel objet et permet la copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operateur d'affectation. Ne copie reellement rien, il initialise simplement un nouvel objet et permet la copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par reference l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaine et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaines. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de references partagees du nombre spécifie. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Determine si la forme doit preserver le rapport d'aspect lors du redimensionnement. Ecriture **bool**. |
| void [set_DrilldownLocked](./set_drilldownlocked/)(**bool**) override | Determine si la selection des sous-formes de cet objet est interdite. Ecriture **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Determine si l'ajout de cette forme a un groupe est interdit. Ecriture **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Determine si le deplacement de cette forme est interdit. Ecriture **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Determine si la selection de cette forme est interdite. Ecriture **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Determine si le redimensionnement de cette forme est interdit. Ecriture **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Definie le n-ieme argument de modele comme pointeur faible (au lieu de partage). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de references partagees. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incremente le compteur de references partagees. Ne doit pas etre appele directement; utilisez plutot les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decremente et renvoie le compteur de references partagees. Ne doit pas etre appele directement; utilisez plutot les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la methode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalises en chaine. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Met en oeuvre la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Met en oeuvre le deverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incremente le compteur de references faibles. Ne doit pas etre appele directement; utilisez plutot les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decremente le compteur de references faibles. Ne doit pas etre appele directement; utilisez plutot les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Detruit l'objet. Libere toutes les structures de donnees internes. |

## Voir aussi

* Classe [BaseShapeLock](../baseshapelock/)
* Classe [IGraphicalObjectLock](../igraphicalobjectlock/)
* Espace de noms [Aspose::Slides](../)
* Bibliotheque [Aspose.Slides](../../)