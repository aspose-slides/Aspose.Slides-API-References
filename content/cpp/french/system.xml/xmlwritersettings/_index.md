---
title: XmlWriterSettings
second_title: Référence de l'API Aspose.Slides pour C++
description: "Spécifie un ensemble de fonctionnalités à prendre en charge sur l'objet XmlWriter créé par la méthode XmlWriter::Create."
type: docs
weight: 586
url: /fr/system.xml/xmlwritersettings/
---
## XmlWriterSettings classe

Spécifie un ensemble de fonctionnalités à prendre en charge sur l'objet [XmlWriter](../xmlwriter/) créé par la méthode [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## Méthodes

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Crée une copie de l’instance [XmlWriterSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Renvoie une valeur indiquant si l’écrivain XML doit vérifier que tous les caractères du document sont conformes à la section "2.2 Characters" du W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Renvoie une valeur indiquant si le [XmlWriter](../xmlwriter/) doit également fermer le flux sous-jacent ou le TextWriter lorsque la méthode [XmlWriter::Close](../xmlwriter/close/) est appelée. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Renvoie le niveau de conformité que l’écrivain XML vérifie dans la sortie XML. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Renvoie une valeur indiquant si le [XmlWriter](../xmlwriter/) n’échappe pas les attributs URI. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Renvoie le type d’encodage de texte à utiliser. |
| **bool** [get_Indent](./get_indent/)() | Renvoie une valeur indiquant s’il faut indenter les éléments. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Renvoie la chaîne de caractères à utiliser lors de l’indentation. Ce paramètre est utilisé lorsque la valeur [XmlWriterSettings::set_Indent](./set_indent/) est définie sur **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Renvoie une valeur indiquant si le [XmlWriter](../xmlwriter/) doit supprimer les déclarations d’espaces de noms dupliquées lors de l’écriture du contenu XML. Le comportement par défaut est que l’écrivain émet toutes les déclarations d’espaces de noms présentes dans le résolveur d’espaces de noms de l’écrivain. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Renvoie la chaîne de caractères à utiliser pour les sauts de ligne. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Renvoie une valeur indiquant s’il faut normaliser les sauts de ligne dans la sortie. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Renvoie une valeur indiquant s’il faut écrire les attributs sur une nouvelle ligne. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Renvoie une valeur indiquant s’il faut omettre une déclaration XML. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Renvoie la méthode utilisée pour sérialiser la sortie [XmlWriter](../xmlwriter/). |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Renvoie une valeur indiquant si le [XmlWriter](../xmlwriter/) ajoutera des balises de fermeture à toutes les balises d’éléments non fermées lorsque la méthode [XmlWriter::Close](../xmlwriter/close/) est appelée. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du montant spécifié. |
| void [Reset](./reset/)() | Réinitialise les membres de la classe de paramètres à leurs valeurs par défaut. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Définit une valeur indiquant si l’écrivain XML doit vérifier que tous les caractères du document sont conformes à la section "2.2 Characters" du W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Définit une valeur indiquant si le [XmlWriter](../xmlwriter/) doit également fermer le flux sous-jacent ou le TextWriter lorsque la méthode [XmlWriter::Close](../xmlwriter/close/) est appelée. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Définit le niveau de conformité que l’écrivain XML vérifie dans la sortie XML. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Définit une valeur indiquant si le [XmlWriter](../xmlwriter/) n’échappe pas les attributs URI. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Définit le type d’encodage de texte à utiliser. |
| void [set_Indent](./set_indent/)(**bool**) | Définit une valeur indiquant s’il faut indenter les éléments. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Définit la chaîne de caractères à utiliser lors de l’indentation. Ce paramètre est utilisé lorsque la valeur [XmlWriterSettings::set_Indent](./set_indent/) est définie sur **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Définit une valeur indiquant si le [XmlWriter](../xmlwriter/) doit supprimer les déclarations d’espaces de noms dupliquées lors de l’écriture du contenu XML. Le comportement par défaut est que l’écrivain émet toutes les déclarations d’espaces de noms présentes dans le résolveur d’espaces de noms de l’écrivain. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Définit la chaîne de caractères à utiliser pour les sauts de ligne. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Définit une valeur indiquant s’il faut normaliser les sauts de ligne dans la sortie. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Définit une valeur indiquant s’il faut écrire les attributs sur une nouvelle ligne. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Définit une valeur indiquant s’il faut omettre une déclaration XML. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Définit une valeur indiquant si le [XmlWriter](../xmlwriter/) ajoutera des balises de fermeture à toutes les balises d’éléments non fermées lorsque la méthode [XmlWriter::Close](../xmlwriter/close/) est appelée. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [XmlWriterSettings](./xmlwritersettings/)() | Initialise une nouvelle instance de la classe [XmlWriterSettings](./). |
| virtual [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias pour un pointeur partagé vers une instance de cette classe. |

## Remarques

Les objets de cette classe ne doivent être alloués qu'avec la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d’instances de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des échecs d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu’argument. 

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)