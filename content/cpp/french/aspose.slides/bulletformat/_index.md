---
title: BulletFormat
second_title: Référence API Aspose.Slides pour C++
description: Représente les propriétés de mise en forme des puces de paragraphe.
type: docs
weight: 248
url: /fr/aspose.slides/bulletformat/
---
## BulletFormat classe

Représente les propriétés de mise en forme des puces de paragraphe.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | Définit les décalages non nuls par défaut pour l'Indent et le MarginLeft effectifs du paragraphe lorsque les puces sont activées (comme PowerPoint le fait si l’on active les puces/la numérotation du paragraphe). Si les puces sont désactivées, réinitialise simplement l'Indent et le MarginLeft du paragraphe (comme PowerPoint le fait si l’on désactive les puces/la numérotation du paragraphe). Les décalages d'indentation sont appliqués en fonction du contexte actuel de la puce – IBulletFormat::get(set)_Type, .NumberedBulletStyle et FontHeight de la première portion. Les décalages d'indentation non nuls sont appliqués à l'Indent et au MarginLeft effectifs du paragraphe courant (rendant les valeurs résultantes locales). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compare avec l'objet spécifié. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence au style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| char16_t [get_Char](./get_char/)() override | Renvoie le caractère de puce d'un paragraphe sans hériter. Lire **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | Renvoie le format couleur d'une puce d'un paragraphe sans hériter. Lecture seule [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | Renvoie la police de puce d'un paragraphe sans hériter. Lecture [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | Renvoie la hauteur de la puce d'un paragraphe sans hériter. La valeur std::numeric_limits<float>::quiet_NaN() indique que la puce hérite de la hauteur de la première portion du paragraphe. Lire **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | Détermine si la puce possède sa propre couleur ou l'hérite de la première portion du paragraphe. **[NullableBool::True](../nullablebool/)** si la puce a sa propre couleur et **[NullableBool::False](../nullablebool/)** si la puce hérite de la couleur de la première portion du paragraphe. Lecture [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | Détermine si la puce possède sa propre police ou l'hérite de la première portion du paragraphe. **[NullableBool::True](../nullablebool/)** si la puce a sa propre police et **[NullableBool::False](../nullablebool/)** si la puce hérite de la police de la première portion du paragraphe. Lecture [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | Renvoie le premier numéro utilisé pour le groupe de puces numérotées sans hériter. Lire **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | Renvoie le style d'une puce numérotée sans hériter. Lecture [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Renvoie l'objet Parent_Immediate. Lecture seule [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Renvoie le parent [IPresentationComponent](../ipresentationcomponent/). Lecture seule [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Renvoie l'image utilisée comme puce dans un paragraphe sans hériter. Lecture seule [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | Renvoie le type de puce d'un paragraphe sans hériter. Lecture [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | Obtient les données de mise en forme effective des puces avec l'héritage appliqué. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Renvoie le code de hachage. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel [System.Object.GetType()](../../system/object/gettype/) en C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appeler directement ou utiliser l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet de cloner des types personnalisés. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie réellement rien, il initialise simplement le nouvel objet et permet de construire des sous-classes par copie. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie réellement rien, il initialise simplement le nouvel objet et permet de construire des sous-classes par copie. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_Char](./set_char/)(char16_t) override | Définit le caractère de puce d'un paragraphe sans hériter. Écrire **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Définit la police de puce d'un paragraphe sans hériter. Écrire [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | Définit la hauteur de la puce d'un paragraphe sans hériter. La valeur std::numeric_limits<float>::quiet_NaN() indique que la puce hérite de la hauteur de la première portion du paragraphe. Écrire **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | Détermine si la puce possède sa propre couleur ou l'hérite de la première portion du paragraphe. **[NullableBool::True](../nullablebool/)** si la puce a sa propre couleur et **[NullableBool::False](../nullablebool/)** si la puce hérite de la couleur de la première portion du paragraphe. Écrire [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | Détermine si la puce possède sa propre police ou l'hérite de la première portion du paragraphe. **[NullableBool::True](../nullablebool/)** si la puce a sa propre police et **[NullableBool::False](../nullablebool/)** si la puce hérite de la police de la première portion du paragraphe. Écrire [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | Définit le premier numéro utilisé pour le groupe de puces numérotées sans hériter. Écrire **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | Définit le style d'une puce numérotée sans hériter. Écrire [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | Définit le type de puce d'un paragraphe sans hériter. Écrire [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appeler directement ou utiliser l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [PVIObject](../pviobject/)
* Classe [IBulletFormat](../ibulletformat/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)