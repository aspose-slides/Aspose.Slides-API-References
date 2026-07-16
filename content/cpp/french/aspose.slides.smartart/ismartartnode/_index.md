---
title: ISmartArtNode
second_title: Référence API Aspose.Slides pour C++
description: Représente un nœud d'un diagramme SmartArt.
type: docs
weight: 14
url: /fr/aspose.slides.smartart/ismartartnode/
---
## ISmartArtNode classe

Représente un nœud d'un diagramme [SmartArt](../smartart/).

```cpp
class ISmartArtNode : public virtual System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_BulletFillFormat](./get_bulletfillformat/)() | Renvoie l'objet [FillFormat](../../aspose.slides/fillformat/) qui contient les propriétés de mise en forme de remplissage pour un puce de nœud. Remarque : peut renvoyer null pour certains types de mise en page [SmartArt](../smartart/) qui ne fournissent pas de puces pour les nœuds. Lecture seule [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](./)\> [get_ChildNode](./get_childnode/)(**int32_t**) | Renvoie un nœud enfant du nœud actuel à l'index spécifié. Lecture seule [Aspose::Slides::SmartArt::ISmartArtNode](./) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_ChildNodes](./get_childnodes/)() | Renvoie les collections de tous les nœuds enfants du nœud actuel. Lecture seule [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual **bool** [get_IsAssistant](./get_isassistant/)() | Renvoie le nœud en tant qu'assistant. Lecture **bool**. |
| virtual **bool** [get_IsHidden](./get_ishidden/)() | Renvoie true si ce nœud est un nœud masqué dans le modèle de données. Lecture seule **bool**. |
| virtual **int32_t** [get_Level](./get_level/)() | Renvoie le niveau d'imbrication du nœud. Lecture seule **int32_t**. |
| virtual [OrganizationChartLayoutType](../organizationchartlayouttype/) [get_OrganizationChartLayout](./get_organizationchartlayout/)() | Renvoie le type de mise en page du diagramme d'organisation associé au nœud actuel. Lecture [OrganizationChartLayoutType](../organizationchartlayouttype/). |
| virtual **int32_t** [get_Position](./get_position/)() | Renvoie la position indexée à zéro du nœud parmi les nœuds frères. Lecture **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtShape](../ismartartshape/)\> [get_Shape](./get_shape/)(**int32_t**) | Renvoie une forme associée à ce nœud à l'index spécifié. Lecture seule [Aspose::Slides::SmartArt::ISmartArtShape](../ismartartshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtShapeCollection](../ismartartshapecollection/)\> [get_Shapes](./get_shapes/)() | Renvoie les collections de toutes les formes associées au nœud. Lecture seule [ISmartArtShapeCollection](../ismartartshapecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() | Renvoie le texte du nœud. Lecture seule [ITextFrame](../../aspose.slides/itextframe/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Met en œuvre le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, vraiment, initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| virtual **bool** [Remove](./remove/)() | Supprime le nœud actuel. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [set_IsAssistant](./set_isassistant/)(**bool**) | Définit le nœud comme assistant. Écriture **bool**. |
| virtual void [set_OrganizationChartLayout](./set_organizationchartlayout/)([OrganizationChartLayoutType](../organizationchartlayouttype/)) | Définit le type de mise en page du diagramme d'organisation associé au nœud actuel. Écriture [OrganizationChartLayoutType](../organizationchartlayouttype/). |
| virtual void [set_Position](./set_position/)(**int32_t**) | Définit la position indexée à zéro du nœud parmi les nœuds frères. Écriture **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉᵐ argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Met en œuvre le construct typeof([System.Object](../../system/object/)) de C#. |
| void [Unlock](../../system/object/unlock/)() | Met en œuvre le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [Aspose::Slides::SmartArt](../)
* Bibliothèque [Aspose.Slides](../../)