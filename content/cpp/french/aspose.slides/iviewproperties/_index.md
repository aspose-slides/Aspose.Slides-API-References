---
title: IViewProperties
second_title: Référence API Aspose.Slides pour C++
description: Propriétés de vue à l'échelle de la présentation.
type: docs
weight: 4239
url: /fr/aspose.slides/iviewproperties/
---
## IViewProperties classe


[Presentation](../presentation/) propriétés de vue large.

```cpp
class IViewProperties : public virtual System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence au style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur au style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual **float** [get_GridSpacing](./get_gridspacing/)() | Renvoie l'espacement de la grille qui doit être utilisé pour la grille sous-jacente du document de présentation, en points. Lecture **float**. |
| virtual [ViewType](../viewtype/) [get_LastView](./get_lastview/)() | Spécifie le mode de vue qui était utilisé lorsque le document de présentation a été enregistré pour la dernière fois. Lecture [ViewType](../viewtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewProperties](../inormalviewproperties/)\> [get_NormalViewProperties](./get_normalviewproperties/)() | Représente les propriétés de vue normale. La vue normale comprend trois régions de contenu : la diapositive elle-même, une région de contenu latérale et une région de contenu inférieure. Lecture seule [INormalViewProperties](../inormalviewproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommonSlideViewProperties](../icommonslideviewproperties/)\> [get_NotesViewProperties](./get_notesviewproperties/)() | Spécifie les propriétés communes de vue associées au mode de vue des notes. Lecture seule [ICommonSlideViewProperties](../icommonslideviewproperties/). |
| virtual [NullableBool](../nullablebool/) [get_ShowComments](./get_showcomments/)() | Spécifie si les commentaires des diapositives doivent être affichés. Lecture [NullableBool](../nullablebool/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommonSlideViewProperties](../icommonslideviewproperties/)\> [get_SlideViewProperties](./get_slideviewproperties/)() | Spécifie les propriétés communes de vue associées au mode de vue des diapositives. Lecture seule [ICommonSlideViewProperties](../icommonslideviewproperties/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de référence associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la copie lors de la construction des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la copie lors de la construction des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de référence partagé de la valeur spécifiée. |
| virtual void [set_GridSpacing](./set_gridspacing/)(**float**) | Définit l'espacement de la grille qui doit être utilisé pour la grille sous-jacente du document de présentation, en points. Écriture **float**. |
| virtual void [set_LastView](./set_lastview/)([ViewType](../viewtype/)) | Spécifie le mode de vue qui était utilisé lorsque le document de présentation a été enregistré pour la dernière fois. Écriture [ViewType](../viewtype/). |
| virtual void [set_ShowComments](./set_showcomments/)([NullableBool](../nullablebool/)) | Spécifie si les commentaires des diapositives doivent être affichés. Écriture [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de référence partagé. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de référence partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de référence partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de référence faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de référence faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)