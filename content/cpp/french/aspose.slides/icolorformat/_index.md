---
title: IColorFormat
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente une couleur utilisée dans une présentation.
type: docs
weight: 1691
url: /fr/aspose.slides/icolorformat/
---
## IColorFormat classe


Représente une couleur utilisée dans une présentation.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Copie le format de couleur depuis \"color\". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual **uint8_t** [get_B](./get_b/)() | Retourne le composant bleu d'une couleur. Toutes les transformations de couleur sont ignorées. Lecture **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Retourne la couleur résultante (avec toutes les transformations de couleur appliquées). Définit les couleurs RVB et supprime toutes les transformations de couleur. Lecture [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Retourne l'opération de transformation de couleur appliquée à la couleur à l'index spécifié. Lecture/écriture [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Retourne la collection des transformations de couleur appliquées à une couleur. Lecture seule [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Retourne la méthode de définition de couleur. Lecture [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Retourne le composant bleu d'une couleur. Toutes les transformations de couleur sont ignorées. Lecture **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Retourne le composant vert d'une couleur. Toutes les transformations de couleur sont ignorées. Lecture **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Retourne le composant rouge d'une couleur. Toutes les transformations de couleur sont ignorées. Lecture **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Retourne le composant vert d'une couleur. Toutes les transformations de couleur sont ignorées. Lecture **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Retourne le composant teinte d'une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Retourne le composant luminance d'une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Retourne le préréglage de couleur. Lecture [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Retourne le composant rouge d'une couleur. Toutes les transformations de couleur sont ignorées. Lecture **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Retourne le composant saturation d'une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Retourne la couleur identifiée par un schéma de couleurs. Lecture [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Retourne la couleur identifiée par la table des couleurs système. Lecture [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Définit le composant bleu d'une couleur. Toutes les transformations de couleur sont ignorées. Écriture **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Retourne la couleur résultante (avec toutes les transformations de couleur appliquées). Définit les couleurs RVB et supprime toutes les transformations de couleur. Écriture [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Définit l'opération de transformation de couleur appliquée à la couleur à l'index spécifié. Lecture/écriture [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Définit la méthode de définition de couleur. Écriture [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Définit le composant bleu d'une couleur. Toutes les transformations de couleur sont ignorées. Écriture **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Définit le composant vert d'une couleur. Toutes les transformations de couleur sont ignorées. Écriture **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Définit le composant rouge d'une couleur. Toutes les transformations de couleur sont ignorées. Écriture **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Définit le composant vert d'une couleur. Toutes les transformations de couleur sont ignorées. Écriture **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Définit le composant teinte d'une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Écriture **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Définit le composant luminance d'une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Écriture **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Définit le préréglage de couleur. Écriture [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Définit le composant rouge d'une couleur. Toutes les transformations de couleur sont ignorées. Écriture **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Définit le composant saturation d'une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Écriture **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Définit la couleur identifiée par un schéma de couleurs. Écriture [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Définit la couleur identifiée par la table des couleurs système. Écriture [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et retourne le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Retourne un [System::String](../../system/string/) qui représente le format de couleur actuel. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le constructeur C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
## Voir aussi

* Classe [IFillParamSource](../ifillparamsource/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)