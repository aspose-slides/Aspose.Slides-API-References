---
title: XmlTextWriter
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un écrivain qui fournit une méthode rapide, non mise en cache et uniquement en avant pour générer des flux ou des fichiers contenant des données XML conformes aux recommandations du W3C Extensible Markup Language (XML) 1.0 et Namespaces in XML.
type: docs
weight: 521
url: /fr/system.xml/xmltextwriter/
---
## XmlTextWriter classe

Représente un écrivain qui fournit une méthode rapide, non mise en cache et uniquement en avant pour générer des flux ou des fichiers contenant des données XML conformes aux recommandations du W3C Extensible Markup Language (XML) 1.0 et Namespaces in XML.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [Close](./close/)() override | Ferme ce flux ainsi que le flux sous-jacent. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Crée une nouvelle instance [XmlWriter](../xmlwriter/) en utilisant le nom de fichier spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crée une nouvelle instance [XmlWriter](../xmlwriter/) en utilisant le nom de fichier et l'objet [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Crée une nouvelle instance [XmlWriter](../xmlwriter/) en utilisant le flux spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crée une nouvelle instance [XmlWriter](../xmlwriter/) en utilisant le flux et l'objet [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Crée une nouvelle instance [XmlWriter](../xmlwriter/) en utilisant le TextWriter spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crée une nouvelle instance [XmlWriter](../xmlwriter/) en utilisant le TextWriter et les objets [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Crée une nouvelle instance [XmlWriter](../xmlwriter/) en utilisant le [Text::StringBuilder](../../system.text/stringbuilder/) spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crée une nouvelle instance [XmlWriter](../xmlwriter/) en utilisant les objets [Text::StringBuilder](../../system.text/stringbuilder/) et [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Crée une nouvelle instance [XmlWriter](../xmlwriter/) en utilisant l'objet [XmlWriter](../xmlwriter/) spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Crée une nouvelle instance [XmlWriter](../xmlwriter/) en utilisant les objets [XmlWriter](../xmlwriter/) et [XmlWriterSettings](../xmlwritersettings/) spécifiés. |
| void [Dispose](../xmlwriter/dispose/)() override | Libère toutes les ressources utilisées par l'instance actuelle de la classe [XmlWriter](../xmlwriter/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| void [Flush](./flush/)() override | Vide le contenu du tampon vers les flux sous-jacent et vide également le flux sous-jacent. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Renvoie l'objet flux sous-jacent. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Indique comment la sortie est formatée. |
| **int32_t** [get_Indentation](./get_indentation/)() | Renvoie le nombre de caractères d'IndentChars à écrire pour chaque niveau de la hiérarchie lorsque [XmlTextWriter::set_Formatting](./set_formatting/) est défini sur [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | Renvoie le caractère à utiliser pour l'indentation lorsque [XmlTextWriter::set_Formatting](./set_formatting/) est défini sur [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | Renvoie une valeur indiquant s'il faut activer la prise en charge des espaces de noms. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Renvoie le caractère à utiliser pour citer les valeurs d'attribut. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Renvoie l'objet [XmlWriterSettings](../xmlwritersettings/) utilisé pour créer cette instance [XmlWriter](../xmlwriter/). |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Renvoie l'état de l'écrivain. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Renvoie la portée actuelle **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Renvoie un XmlSpace représentant la portée actuelle **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Renvoie le préfixe le plus proche défini dans la portée actuelle de l'espace de noms pour l'URI de l'espace de noms. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la copie lors de la construction des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la copie lors de la construction des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Indique comment la sortie est formatée. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Définit le nombre de caractères d'IndentChars à écrire pour chaque niveau de la hiérarchie lorsque [XmlTextWriter::set_Formatting](./set_formatting/) est défini sur [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Définit le caractère à utiliser pour l'indentation lorsque [XmlTextWriter::set_Formatting](./set_formatting/) est défini sur [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Définit une valeur indiquant s'il faut activer la prise en charge des espaces de noms. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Définit le caractère à utiliser pour citer les valeurs d'attribut. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Lorsqu'il est redéfini dans une classe dérivée, écrit tous les attributs trouvés à la position actuelle dans le [XmlReader](../xmlreader/). |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lorsqu'il est redéfini dans une classe dérivée, écrit un attribut avec le nom local, l'URI de l'espace de noms et la valeur spécifiés. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lorsqu'il est redéfini dans une classe dérivée, écrit l'attribut avec le nom local et la valeur spécifiés. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lorsqu'il est redéfini dans une classe dérivée, écrit l'attribut avec le préfixe, le nom local, l'URI de l'espace de noms et la valeur spécifiés. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Encode les octets binaires spécifiés en base64 et écrit le texte résultant. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Encode les octets binaires spécifiés en binhex et écrit le texte résultant. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Écrit un bloc **...** contenant le texte spécifié. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Force la génération d'une entité de caractère pour la valeur Unicode spécifiée. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Écrit le texte un tampon à la fois. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Écrit un commentaire **** contenant le texte spécifié. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Écrit la déclaration DOCTYPE avec le nom spécifié et les attributs optionnels. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Écrit un élément avec le nom local et la valeur spécifiés. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Écrit un élément avec le nom local, l'URI de l'espace de noms et la valeur spécifiés. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Écrit un élément avec le préfixe, le nom local, l'URI de l'espace de noms et la valeur spécifiés. |
| void [WriteEndAttribute](./writeendattribute/)() override | Ferme l'appel [XmlTextWriter::WriteStartAttribute](./writestartattribute/) précédent. |
| void [WriteEndDocument](./writeenddocument/)() override | Ferme tous les éléments ou attributs ouverts et remet l'écrivain à l'état Start. |
| void [WriteEndElement](./writeendelement/)() override | Ferme un élément et dépile la portée d'espace de noms correspondante. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Écrit une référence d'entité sous la forme **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | Ferme un élément et dépile la portée d'espace de noms correspondante. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Écrit le nom spécifié, en s'assurant qu'il s'agit d'un nom valide selon le [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Écrit le nom spécifié, en s'assurant qu'il s'agit d'un **NmToken** valide selon le [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Lorsqu'il est redéfini dans une classe dérivée, copie tout du lecteur à l'écrivain et déplace le lecteur au début du frère suivant. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Copie tout de l'objet XPathNavigator à l'écrivain. La position de XPathNavigator reste inchangée. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Écrit une instruction de traitement avec un espace entre le nom et le texte comme suit : **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Écrit le nom qualifié par l'espace de noms. Cette méthode recherche le préfixe en vigueur pour l'espace de noms donné. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Écrit du balisage brut manuellement à partir d'un tampon de caractères. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Écrit du balisage brut manuellement à partir d'une chaîne. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Écrit le début d'un attribut. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Écrit le début d'un attribut avec le nom local et l'URI de l'espace de noms spécifiés. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Écrit le début d'un attribut avec le nom local spécifié. |
| void [WriteStartDocument](./writestartdocument/)() override | Écrit la déclaration XML avec la version "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Écrit la déclaration XML avec la version "1.0" et l'attribut standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Écrit la balise d'ouverture spécifiée et l'associe à l'espace de noms et au préfixe donnés. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lorsqu'il est redéfini dans une classe dérivée, écrit la balise d'ouverture spécifiée et l'associe à l'espace de noms donné. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | Lorsqu'il est redéfini dans une classe dérivée, écrit une balise d'ouverture avec le nom local spécifié. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Écrit le contenu texte fourni. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Génère et écrit l'entité de caractère de substitution pour la paire de caractères de substitution. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Écrit la valeur de l'objet. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Écrit une valeur [String](../../system/string/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Écrit une valeur [Boolean](../../system/boolean/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Écrit une valeur [DateTime](../../system/datetime/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Écrit une valeur [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Écrit une valeur [Double](../../system/double/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Écrit un nombre à virgule flottante simple précision. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Écrit une valeur [Decimal](../../system/decimal/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Écrit une valeur [Int32](../../system/int32/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Écrit une valeur [Int64](../../system/int64/). |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Écrit l'espace blanc fourni. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Crée une instance de la classe [XmlTextWriter](./) en utilisant le flux et l'encodage spécifiés. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Crée une instance de la classe [XmlTextWriter](./) en utilisant le fichier spécifié. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Crée une instance de la classe [XmlTextWriter](./) en utilisant le TextWriter spécifié. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias pour un pointeur partagé vers une instance de cette classe. |
## Remarques

Il est recommandé d'utiliser la classe [XmlWriter](../xmlwriter/) à la place. 

Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instances de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Toujours encapsuler cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utiliser ce pointeur pour le passer aux fonctions en tant qu'argument. 

## Voir aussi

* Classe [XmlWriter](../xmlwriter/)
* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)