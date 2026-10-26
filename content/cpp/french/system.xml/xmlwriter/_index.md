---
title: XmlWriter
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un écrivain qui fournit une méthode rapide, non mise en cache et uniquement en avant pour générer des flux ou des fichiers contenant des données XML.
type: docs
weight: 573
url: /fr/system.xml/xmlwriter/
---
## XmlWriter classe

Représente un écrivain qui fournit une méthode rapide, non mise en cache et uniquement en avant pour générer des flux ou des fichiers contenant des données XML.

```cpp
class XmlWriter : public System::IDisposable
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual void [Close](./close/)() | Lorsqu'il est remplacé dans une classe dérivée, ferme ce flux et le flux sous-jacent. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Crée une nouvelle instance [XmlWriter](./) en utilisant le nom de fichier spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crée une nouvelle instance [XmlWriter](./) en utilisant le nom de fichier et l'objet [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Crée une nouvelle instance [XmlWriter](./) en utilisant le flux spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crée une nouvelle instance [XmlWriter](./) en utilisant le flux et l'objet [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Crée une nouvelle instance [XmlWriter](./) en utilisant le TextWriter spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crée une nouvelle instance [XmlWriter](./) en utilisant le TextWriter et les objets [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Crée une nouvelle instance [XmlWriter](./) en utilisant le [Text::StringBuilder](../../system.text/stringbuilder/) spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crée une nouvelle instance [XmlWriter](./) en utilisant les objets [Text::StringBuilder](../../system.text/stringbuilder/) et [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Crée une nouvelle instance [XmlWriter](./) en utilisant l'objet [XmlWriter](./) spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crée une nouvelle instance [XmlWriter](./) en utilisant les objets [XmlWriter](./) et [XmlWriterSettings](../xmlwritersettings/) spécifiés. |
| void [Dispose](./dispose/)() override | Libère toutes les ressources utilisées par l'instance actuelle de la classe [XmlWriter](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| virtual void [Flush](./flush/)() | Lorsqu'il est remplacé dans une classe dérivée, vide tout le contenu du tampon vers les flux sous-jacents et vide également le flux sous-jacent. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Renvoie l'objet [XmlWriterSettings](../xmlwritersettings/) utilisé pour créer cette instance [XmlWriter](./). |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | Lorsqu'il est remplacé dans une classe dérivée, récupère l'état de l'écrivain. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Lorsqu'il est remplacé dans une classe dérivée, obtient la portée actuelle **xml:lang**. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Lorsqu'il est remplacé dans une classe dérivée, obtient un XmlSpace représentant la portée actuelle **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | Lorsqu'il est remplacé dans une classe dérivée, renvoie le préfixe le plus proche défini dans la portée d'espace de noms actuelle pour l'URI d'espace de noms. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il se contente d'initialiser un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il se contente d'initialiser un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Lorsqu'il est remplacé dans une classe dérivée, écrit tous les attributs trouvés à la position actuelle dans le [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit un attribut avec le nom local, l'URI d'espace de noms et la valeur spécifiés. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit l'attribut avec le nom local et la valeur spécifiés. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit l'attribut avec le préfixe, le nom local, l'URI d'espace de noms et la valeur spécifiés. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Lorsqu'il est remplacé dans une classe dérivée, encode les octets binaires spécifiés en Base64 et écrit le texte résultant. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Lorsqu'il est remplacé dans une classe dérivée, encode les octets binaires spécifiés en **BinHex** et écrit le texte résultant. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | Lorsqu'il est remplacé dans une classe dérivée, écrit un bloc **...** contenant le texte spécifié. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | Lorsqu'il est remplacé dans une classe dérivée, force la génération d'une entité de caractère pour la valeur Unicode du caractère spécifié. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Lorsqu'il est remplacé dans une classe dérivée, écrit le texte un tampon à la fois. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | Lorsqu'il est remplacé dans une classe dérivée, écrit un commentaire **** contenant le texte spécifié. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit la déclaration DOCTYPE avec le nom spécifié et les attributs optionnels. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Écrit un élément avec le nom local et la valeur spécifiés. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Écrit un élément avec le nom local, l'URI d'espace de noms et la valeur spécifiés. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Écrit un élément avec le préfixe, le nom local, l'URI d'espace de noms et la valeur spécifiés. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | Lorsqu'il est remplacé dans une classe dérivée, ferme l'appel précédent XmlWriter::WriteStartAttribute(String,String). |
| virtual void [WriteEndDocument](./writeenddocument/)() | Lorsqu'il est remplacé dans une classe dérivée, ferme tous les éléments ou attributs ouverts et remet l'écrivain dans l'état Start. |
| virtual void [WriteEndElement](./writeendelement/)() | Lorsqu'il est remplacé dans une classe dérivée, ferme un élément et dépile la portée d'espace de noms correspondante. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit une référence d'entité sous la forme **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | Lorsqu'il est remplacé dans une classe dérivée, ferme un élément et dépile la portée d'espace de noms correspondante. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit le nom spécifié, en s'assurant qu'il s'agit d'un nom valide selon la recommandation W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit le nom spécifié, en s'assurant qu'il s'agit d'un NmToken valide selon la recommandation W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Lorsqu'il est remplacé dans une classe dérivée, copie tout du lecteur vers l'écrivain et déplace le lecteur au début du frère suivant. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Copie tout de l'objet XPathNavigator vers l'écrivain. La position du XPathNavigator reste inchangée. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | Lorsqu'il est remplacé dans une classe dérivée, écrit une instruction de traitement avec un espace entre le nom et le texte comme suit : **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit le nom qualifié par l'espace de noms. Cette méthode recherche le préfixe en vigueur pour l'espace de noms donné. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Lorsqu'il est remplacé dans une classe dérivée, écrit du balisage brut manuellement depuis un tampon de caractères. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit du balisage brut manuellement depuis une chaîne. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Écrit le début d'un attribut avec le nom local et l'URI d'espace de noms spécifiés. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit le début d'un attribut avec le préfixe, le nom local et l'URI d'espace de noms spécifiés. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Écrit le début d'un attribut avec le nom local spécifié. |
| virtual void [WriteStartDocument](./writestartdocument/)() | Lorsqu'il est remplacé dans une classe dérivée, écrit la déclaration XML avec la version "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | Lorsqu'il est remplacé dans une classe dérivée, écrit la déclaration XML avec la version "1.0" et l'attribut standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit la balise de début spécifiée et l'associe à l'espace de noms donné. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit la balise de début spécifiée et l'associe à l'espace de noms et au préfixe donnés. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit une balise de début avec le nom local spécifié. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Lorsqu'il est remplacé dans une classe dérivée, écrit le contenu texte fourni. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Lorsqu'il est remplacé dans une classe dérivée, génère et écrit l'entité de caractère de substitution pour la paire de caractères de substitution. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Écrit la valeur de l'objet. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Écrit une valeur [String](../../system/string/). |
| virtual void [WriteValue](./writevalue/)(**bool**) | Écrit une valeur [Boolean](../../system/boolean/). |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Écrit une valeur [DateTime](../../system/datetime/). |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Écrit une valeur [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](./writevalue/)(**double**) | Écrit une valeur [Double](../../system/double/). |
| virtual void [WriteValue](./writevalue/)(**float**) | Écrit un nombre à virgule flottante simple précision. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Écrit une valeur [Decimal](../../system/decimal/). |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Écrit une valeur [Int32](../../system/int32/). |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Écrit une valeur [Int64](../../system/int64/). |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | Lorsqu'il est remplacé dans une classe dérivée, écrit l'espace blanc fourni. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias pour un pointeur partagé vers une instance de cette classe. |

## Voir aussi

* Classe [IDisposable](../../system/idisposable/)
* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)