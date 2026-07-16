---
title: PresentationFactory
second_title: Aspose.Slides pour C++ Référence de l'API
description: Permet de créer une présentation via l'interface COM
type: docs
weight: 4850
url: /fr/aspose.slides/presentationfactory/
---
## classe PresentationFactory


Allows to create presentation via COM interface

```cpp
class PresentationFactory : public Aspose::Slides::IPresentationFactory
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [CreatePresentation](./createpresentation/)() override | Crée une nouvelle présentation. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [CreatePresentation](./createpresentation/)([System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Crée une nouvelle présentation avec des options de chargement supplémentaires |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| static [System::SharedPtr](../../system/sharedptr/)\<[PresentationFactory](./)\> [get_Instance](./get_instance/)() | [Presentation](../presentation/) instance statique du factory. En lecture seule [PresentationFactory](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationInfo](../ipresentationinfo/)\> [GetPresentationInfo](./getpresentationinfo/)([System::String](../../system/string/)) override | Crée un nouvel objet [PresentationInfo](../presentationinfo/) à partir d'un fichier et lie la présentation à celui-ci. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationInfo](../ipresentationinfo/)\> [GetPresentationInfo](./getpresentationinfo/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Crée un nouvel objet [PresentationInfo](../presentationinfo/) à partir d'un flux et lie la présentation à celui-ci. Obtient des informations sur la présentation dans le flux spécifié. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationText](../ipresentationtext/)\> [GetPresentationText](./getpresentationtext/)([System::String](../../system/string/), [TextExtractionArrangingMode](../textextractionarrangingmode/)) override | Récupère le texte brut des diapositives. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationText](../ipresentationtext/)\> [GetPresentationText](./getpresentationtext/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [TextExtractionArrangingMode](../textextractionarrangingmode/)) override | Récupère le texte brut des diapositives. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationText](../ipresentationtext/)\> [GetPresentationText](./getpresentationtext/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [TextExtractionArrangingMode](../textextractionarrangingmode/), [System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Récupère le texte brut des diapositives. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet aux sous-classes de se copier. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'assignation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet aux sous-classes de se copier. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Lit une présentation existante à partir d'un tableau. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Lit une présentation existante à partir d'un tableau avec des options de chargement supplémentaires. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Lit une présentation existante à partir d'un flux. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Lit une présentation existante à partir d'un flux avec des options de chargement supplémentaires. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::String](../../system/string/)) override | Lit une présentation existante à partir d'un fichier. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Lit une présentation existante à partir d'un flux avec des options de chargement supplémentaires. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n'th argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct typeof([System.Object](../../system/object/)) de C#. |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Remarques


L'exemple suivant montre comment vérifier un format [Presentation](../presentation/).
```cpp
System::SharedPtr<IPresentationInfo> info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
System::Console::WriteLine(System::ExplicitCast<System::Object>(info->get_LoadFormat())); // PPTX
System::SharedPtr<IPresentationInfo> info2 = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.ppt");
System::Console::WriteLine(System::ExplicitCast<System::Object>(info2->get_LoadFormat())); // PPT
System::SharedPtr<IPresentationInfo> info3 = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.odp");
System::Console::WriteLine(System::ExplicitCast<System::Object>(info3->get_LoadFormat())); // ODP
```
 L'exemple suivant montre comment obtenir les propriétés d'un [Presentation](../presentation/).
```cpp
System::SharedPtr<IPresentationInfo> info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
System::SharedPtr<IDocumentProperties> props = info->ReadDocumentProperties();
System::Console::WriteLine(System::ExplicitCast<System::Object>(props->get_CreatedTime()));
System::Console::WriteLine(props->get_Subject());
System::Console::WriteLine(props->get_Title());
```
 L'exemple suivant montre comment mettre à jour les propriétés d'un [Presentation](../presentation/).
```cpp
System::SharedPtr<IPresentationInfo> info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
System::SharedPtr<IDocumentProperties> props = info->ReadDocumentProperties();
props->set_Title(u"My title");
info->UpdateDocumentProperties(props);
```

## Voir aussi

* Classe [IPresentationFactory](../ipresentationfactory/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)