---
title: Rotation3D
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente la rotation 3D d'un graphique.
type: docs
weight: 1327
url: /fr/aspose.slides.charts/rotation3d/
---
## Rotation3D classe


Représente la rotation 3D d'un graphique.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence en style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur en style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Renvoie la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 pour cent). Lire **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Spécifie la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 pour cent). Lire **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | Renvoie la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 240). Ignorée si la valeur de la propriété RightAngleAxes est vraie. Lire **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. En d'autres termes, cela détermine si les angles des axes du graphique sont indépendants de la rotation ou de l'élévation du graphique. Lire **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | Renvoie le degré de rotation autour de l'axe X, c'est-à-dire dans la direction Y pour les graphiques 3D (entre -90 et 90 degrés). La propriété correspond à l'élément 21.2.2.157 rotX (Rotation X) du ECMA-376 et à l'option \"Y Rotation\" dans PowerPoint 2007+. Lire **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Renvoie le degré de rotation autour de l'axe Y, c'est-à-dire dans la direction X pour les graphiques 3D (entre 0 et 360 degrés). La propriété correspond à l'élément 21.2.2.158 rotY (Rotation Y) du ECMA-376 et à l'option \"X Rotation\" dans PowerPoint 2007+. Lire **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Met en œuvre le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction de copies de sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction de copies de sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 pour cent). Écrire **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Spécifie la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 pour cent). Écrire **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | Définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 240). Ignorée si la valeur de la propriété RightAngleAxes est vraie. Écrire **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. En d'autres termes, cela détermine si les angles des axes du graphique sont indépendants de la rotation ou de l'élévation du graphique. Écrire **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | Définit le degré de rotation autour de l'axe X, c'est-à-dire dans la direction Y pour les graphiques 3D (entre -90 et 90 degrés). La propriété correspond à l'élément 21.2.2.157 rotX (Rotation X) du ECMA-376 et à l'option \"Y Rotation\" dans PowerPoint 2007+. Écrire **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Définit le degré de rotation autour de l'axe Y, c'est-à-dire dans la direction X pour les graphiques 3D (entre 0 et 360 degrés). La propriété correspond à l'élément 21.2.2.158 rotY (Rotation Y) du ECMA-376 et à l'option \"X Rotation\" dans PowerPoint 2007+. Écrire **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Met en œuvre la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Met en œuvre le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IRotation3D](../irotation3d/)
* Classe [IDOMObject](../../aspose.slides/idomobject/)
* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)