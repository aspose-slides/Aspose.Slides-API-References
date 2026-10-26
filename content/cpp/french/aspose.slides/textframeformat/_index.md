---
title: TextFrameFormat
second_title: Référence de l'API Aspose.Slides pour C++
description: Contient les propriétés formatTextFrameFormatting du TextFrame.
type: docs
weight: 5461
url: /fr/aspose.slides/textframeformat/
---
## TextFrameFormat classe

Contient les propriétés formatTextFrameFormatting de [TextFrame](../textframe/).

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compare avec l'objet spécifié. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Renvoie le texte d'ancrage vertical dans un [TextFrame](../textframe/). Lire [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Renvoie le mode d'ajustement automatique du texte. Lire [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | Si [NullableBool::True](../nullablebool/) alors le texte doit être centré horizontalement dans la boîte. Lire [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Renvoie le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera fixée à zéro. La valeur 0 signifie valeur non définie. Lire **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Renvoie l'espace entre les colonnes de texte dans la zone de texte (en points). Cela ne doit s'appliquer que lorsqu'il y a plus d'une colonne. Cette valeur doit être un nombre positif. Sinon, la valeur sera fixée à zéro. Lire **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | Obtient le maintien du texte à plat même si un effet de rotation 3D a été appliqué. Lire **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Renvoie la marge inférieure (points) dans un [TextFrame](../textframe/). Lire **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Renvoie la marge gauche (points) dans un [TextFrame](../textframe/). Lire **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Renvoie la marge droite (points) dans un [TextFrame](../textframe/). Lire **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Renvoie la marge supérieure (points) dans un [TextFrame](../textframe/). Lire **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Renvoie l'objet Parent_Immediate. Lecture seule [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Renvoie le parent [IPresentationComponent](../ipresentationcomponent/). Lecture seule [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Spécifie la rotation personnalisée appliquée au texte dans la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation du texte. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lire **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Détermine l'orientation du texte. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et de l'angle personnalisé dans la propriété RotationAngle. Lire [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Renvoie l'objet [ThreeDFormat](../threedformat/) qui représente les propriétés d'effet 3D pour un texte. Lecture seule [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Obtient la forme d'habillage du texte. Lire [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** si le texte est enveloppé aux marges de [TextFrame](../textframe/). Lire [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Obtient les données de formatage effectif du cadre de texte avec l'héritage appliqué. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Renvoie le code de hachage. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il se contente d'initialiser un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il se contente d'initialiser un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | Définit le texte d'ancrage vertical dans un [TextFrame](../textframe/). Écrire [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Définit le mode d'ajustement automatique du texte. Écrire [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | Si [NullableBool::True](../nullablebool/) alors le texte doit être centré horizontalement dans la boîte. Écrire [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera fixée à zéro. La valeur 0 signifie valeur non définie. Écrire **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Définit l'espace entre les colonnes de texte dans la zone de texte (en points). Cela ne doit s'appliquer que lorsqu'il y a plus d'une colonne. Cette valeur doit être un nombre positif. Sinon, la valeur sera fixée à zéro. Écrire **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | Définit le maintien du texte à plat même si un effet de rotation 3D a été appliqué. Écrire **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Définit la marge inférieure (points) dans un [TextFrame](../textframe/). Écrire **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Définit la marge gauche (points) dans un [TextFrame](../textframe/). Écrire **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Définit la marge droite (points) dans un [TextFrame](../textframe/). Écrire **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Définit la marge supérieure (points) dans un [TextFrame](../textframe/). Écrire **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Spécifie la rotation personnalisée appliquée au texte dans la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation du texte. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Écrire **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Détermine l'orientation du texte. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et de l'angle personnalisé dans la propriété RotationAngle. Écrire [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Définit la forme d'habillage du texte. Écrire [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** si le texte est enveloppé aux marges de [TextFrame](../textframe/). Écrire [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
|  [TextFrameFormat](./textframeformat/)() | Initialise une nouvelle instance de la classe [TextFrameFormat](./). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [PVIObject](../pviobject/)
* Classe [ITextFrameFormat](../itextframeformat/)
* Classe [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)