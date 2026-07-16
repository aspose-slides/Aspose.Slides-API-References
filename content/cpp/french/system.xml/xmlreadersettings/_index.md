---
title: XmlReaderSettings
second_title: Référence API Aspose.Slides pour C++
description: "Spécifie un ensemble de fonctionnalités à prendre en charge sur l'objet XmlReader créé par la méthode XmlReader::Create."
type: docs
weight: 443
url: /fr/system.xml/xmlreadersettings/
---
## XmlReaderSettings classe


Spécifie un ensemble de fonctionnalités à prendre en charge sur l'objet [XmlReader](../xmlreader/) créé par la méthode [XmlReader::Create](../xmlreader/create/).

```cpp
class XmlReaderSettings : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Crée une copie de l'instance [XmlReaderSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de type C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de type C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Renvoie une valeur indiquant s'il faut effectuer la vérification des caractères. |
| **bool** [get_CloseInput](./get_closeinput/)() | Renvoie une valeur indiquant si le flux sous-jacent ou le TextReader doit être fermé lorsque le lecteur est fermé. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Renvoie le niveau de conformité auquel [XmlReader](../xmlreader/) se conforme. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Renvoie une valeur qui détermine le traitement des DTD. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Renvoie une valeur indiquant s'il faut ignorer les commentaires. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Renvoie une valeur indiquant s'il faut ignorer les instructions de traitement. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Renvoie une valeur indiquant s'il faut ignorer les espaces blancs insignifiants. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Renvoie le décalage du numéro de ligne de l'objet [XmlReader](../xmlreader/). |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Renvoie le décalage de la position de ligne de l'objet [XmlReader](../xmlreader/). |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Renvoie une valeur indiquant le nombre maximal autorisé de caractères dans un document résultant de l'expansion des entités. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Renvoie une valeur indiquant le nombre maximal autorisé de caractères dans un document XML. Une valeur zéro (0) signifie qu'il n’y a aucune limite sur la taille du document XML. Une valeur non nulle spécifie la taille maximale, en caractères. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Renvoie le [XmlNameTable](../xmlnametable/) utilisé pour les comparaisons de chaînes atomisées. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Renvoie une valeur indiquant s'il faut interdire le traitement des définitions de type de document (DTD). |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Renvoie le XmlSchemaSet à utiliser lors de la validation du schéma. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Renvoie une valeur indiquant les paramètres de validation du schéma. Ce paramètre s'applique aux objets [XmlReader](../xmlreader/) qui valident les schémas (la valeur [XmlReaderSettings::get_ValidationType](./get_validationtype/) est [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Renvoie une valeur indiquant si [XmlReader](../xmlreader/) effectuera la validation ou l'attribution de type lors de la lecture. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [Reset](./reset/)() | Réinitialise les membres de la classe de paramètres à leurs valeurs par défaut. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Définit une valeur indiquant s'il faut effectuer la vérification des caractères. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Définit une valeur indiquant si le flux sous-jacent ou le TextReader doit être fermé lorsque le lecteur est fermé. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Définit le niveau de conformité auquel [XmlReader](../xmlreader/) doit se conformer. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Définit une valeur qui détermine le traitement des DTD. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Définit une valeur indiquant s'il faut ignorer les commentaires. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Définit une valeur indiquant s'il faut ignorer les instructions de traitement. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Définit une valeur indiquant s'il faut ignorer les espaces blancs insignifiants. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Définit le décalage du numéro de ligne de l'objet [XmlReader](../xmlreader/). |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Définit le décalage de la position de ligne de l'objet [XmlReader](../xmlreader/). |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Définit une valeur indiquant le nombre maximal autorisé de caractères dans un document résultant de l'expansion des entités. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Définit une valeur indiquant le nombre maximal autorisé de caractères dans un document XML. Une valeur zéro (0) signifie qu'il n’y a aucune limite sur la taille du document XML. Une valeur non nulle spécifie la taille maximale, en caractères. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Définit le [XmlNameTable](../xmlnametable/) utilisé pour les comparaisons de chaînes atomisées. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Définit une valeur indiquant s'il faut interdire le traitement des définitions de type de document (DTD). |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Définit le XmlSchemaSet à utiliser lors de la validation du schéma. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Définit une valeur indiquant les paramètres de validation du schéma. Ce paramètre s'applique aux objets [XmlReader](../xmlreader/) qui valident les schémas (la valeur [XmlReaderSettings::get_ValidationType](./get_validationtype/) est [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Définit une valeur indiquant si [XmlReader](../xmlreader/) effectuera la validation ou l'attribution de type lors de la lecture. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Définit le [XmlResolver](../xmlresolver/) utilisé pour accéder aux documents externes. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉ argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Ajoute un gestionnaire d'événement déclenché lorsque le lecteur rencontre des erreurs de validation. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Supprime un gestionnaire d'événement déclenché lorsque le lecteur rencontre des erreurs de validation. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Initialise une nouvelle instance de la classe [XmlReaderSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias pour un pointeur partagé vers une instance de cette classe. |

## Remarques

Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instances de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. 

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)