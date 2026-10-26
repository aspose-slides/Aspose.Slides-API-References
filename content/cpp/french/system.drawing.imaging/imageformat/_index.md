---
title: ImageFormat
second_title: Référence API Aspose.Slides pour C++
description: "Représente le format de fichier d'une image. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 131
url: /fr/system.drawing.imaging/imageformat/
---
## ImageFormat classe


Représente le format de fichier d'une image. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument.

```cpp
class ImageFormat : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [Equals](./equals/)([ImageFormatPtr](../imageformatptr/)) const | Détermine si les formats d’image représentés par les objets actuel et spécifié sont égaux. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence au style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| static [ImageFormatPtr](../imageformatptr/) [get_Bmp](./get_bmp/)() | Retourne un pointeur partagé vers un objet [ImageFormat](./) qui représente le format d’image bitmap. |
| static [ImageFormatPtr](../imageformatptr/) [get_Emf](./get_emf/)() | Retourne un pointeur partagé vers un objet [ImageFormat](./) qui représente le format de métafichier enrichi. |
| static [ImageFormatPtr](../imageformatptr/) [get_Exif](./get_exif/)() | Retourne un pointeur partagé vers un objet [ImageFormat](./) qui représente le format du fichier Exchangeable [Image](../../system.drawing/image/) (Exif). |
| static [ImageFormatPtr](../imageformatptr/) [get_Gif](./get_gif/)() | Retourne un pointeur partagé vers un objet [ImageFormat](./) qui représente le format d’image [Graphics](../../system.drawing/graphics/) Interchange Format (GIF). |
| [System::Guid](../../system/guid/) [get_Guid](./get_guid/)() const | Retourne le GUID associé au format d’image représenté par l’objet actuel. |
| static [ImageFormatPtr](../imageformatptr/) [get_Icon](./get_icon/)() | Retourne un pointeur partagé vers un objet [ImageFormat](./) qui représente le format d’image icône [Windows](../../system.windows/). |
| static [ImageFormatPtr](../imageformatptr/) [get_Jpeg](./get_jpeg/)() | Retourne un pointeur partagé vers un objet [ImageFormat](./) qui représente le format d’image Joint Photographic Experts Group (JPEG). |
| static [ImageFormatPtr](../imageformatptr/) [get_MemoryBmp](./get_memorybmp/)() | Retourne un pointeur partagé vers un objet [ImageFormat](./) qui représente le format d’un bitmap en mémoire. |
| static [ImageFormatPtr](../imageformatptr/) [get_Png](./get_png/)() | Retourne un pointeur partagé vers un objet [ImageFormat](./) qui représente le format d’image W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG). |
| static [ImageFormatPtr](../imageformatptr/) [get_Tiff](./get_tiff/)() | Retourne un pointeur partagé vers un objet [ImageFormat](./) qui représente le format d’image Tagged [Image](../../system.drawing/image/) File Format (TIFF). |
| static [ImageFormatPtr](../imageformatptr/) [get_Wmf](./get_wmf/)() | Retourne un pointeur partagé vers un objet [ImageFormat](./) qui représente le format de métafichier [Windows](../../system.windows/) (WMF). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel [System.Object.GetType()](../../system/object/gettype/) de C#. |
| [ImageFormat](./imageformat/)(const [System::Guid](../../system/guid/)\&) | Construit une instance de la classe [ImageFormat](./) qui représente un format d’image associé au GUID spécifié. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permet le clonage de types personnalisés. |
| [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de passer les pointeurs des conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)() const | Convertit cet objet [ImageFormat](./) en une chaîne lisible par l’humain. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [System::Drawing::Imaging](../)
* Bibliothèque [Aspose.Slides](../../)