---
title: ICell
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente une cellule dans un tableau.
type: docs
weight: 1639
url: /fr/aspose.slides/icell/
---
## ICell classe

Représente une cellule dans un tableau.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Détermine si la zone de texte est centrée à l’intérieur d’une cellule. Lecture **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Renvoie l’objet [CellFormat](../cellformat/) qui contient les propriétés de formatage pour cette cellule. Lecture seule [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Renvoie le nombre de colonnes de la grille du tableau parent qui doivent être englobées par la cellule actuelle. Cette propriété permet aux cellules d’avoir l’apparence d’être fusionnées, car elles traversent les bordures verticales des autres cellules du tableau. Lecture seule **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Obtient la première colonne de la cellule. Lecture seule [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Renvoie l’indice de la première colonne couverte par la cellule. Lecture seule **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Obtient la première ligne de la cellule. Lecture seule [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Renvoie l’indice de la première ligne couverte par la cellule. Lecture seule **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Renvoie la hauteur de la cellule. Lecture seule **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Renvoie true si la cellule est fusionnée avec une autre cellule ajustée, false sinon. Lecture seule **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Renvoie la marge inférieure dans un [TextFrame](../textframe/). Lecture **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Renvoie la marge gauche dans un [TextFrame](../textframe/). Lecture **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Renvoie la marge droite dans un [TextFrame](../textframe/). Lecture **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Renvoie la marge supérieure dans un [TextFrame](../textframe/). Lecture **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Renvoie la hauteur minimale d’une cellule. Il s’agit de la somme des hauteurs minimales de toutes les lignes couvertes par la cellule. Lecture seule **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Renvoie la distance du côté gauche du tableau au côté gauche de la cellule. Lecture seule **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Renvoie la distance du côté supérieur du tableau au côté supérieur de la cellule. Lecture seule **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Renvoie la présentation. Lecture seule [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Renvoie le nombre de lignes englobées par une cellule fusionnée. Ceci est utilisé en combinaison avec l’attribut vMerge sur d’autres cellules afin de spécifier la cellule de départ d’une fusion horizontale. Lecture seule **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Renvoie la diapositive de base. Lecture seule [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Renvoie l’objet parent [Table](../table/) d’une cellule. Lecture seule [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Renvoie le type d’ancrage du texte. Lecture [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Renvoie le cadre de texte d’une cellule. Lecture seule [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Renvoie le type de texte vertical. Lecture [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Renvoie la largeur de la cellule. Lecture seule **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Détermine si la zone de texte est centrée à l’intérieur d’une cellule. Écriture **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Définit la marge inférieure dans un [TextFrame](../textframe/). Écriture **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Définit la marge gauche dans un [TextFrame](../textframe/). Écriture **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Définit la marge droite dans un [TextFrame](../textframe/). Écriture **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Définit la marge supérieure dans un [TextFrame](../textframe/). Écriture **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Définit le type d’ancrage du texte. Écriture [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Définit le type de texte vertical. Écriture [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définir le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Diminue et renvoie le compteur de références partagées. Ne doit pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Divise la cellule en deux cellules selon l’indice de colonne. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Divise la cellule selon la hauteur. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Divise la cellule en deux cellules selon l’indice de ligne. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Divise la cellule selon la largeur. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Diminue le compteur de références faibles. Ne doit pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [ISlideComponent](../islidecomponent/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)