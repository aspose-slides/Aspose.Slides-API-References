---
title: "System::Xml"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 1119
url: /fr/system.xml/
---
## Classes

| Classe | Description |
| --- | --- |
| [Details_XmlException](./details_xmlexception/) | Renvoie des informations détaillées sur la dernière exception. |
| [IApplicationResourceStreamResolver](./iapplicationresourcestreamresolver/) | Représente un résolveur de flux de ressources d'application. |
| [IHasXmlNode](./ihasxmlnode/) | Permet à une classe de renvoyer un [XmlNode](./xmlnode/) depuis le contexte ou la position actuelle. |
| [IXmlLineInfo](./ixmllineinfo/) | Fournit une interface permettant à une classe de renvoyer des informations de ligne et de position. |
| [IXmlNamespaceResolver](./ixmlnamespaceresolver/) | Fournit un accès en lecture seule à un ensemble de préfixes et de mappages d'espaces de noms. |
| [NameTable](./nametable/) | Implémente un [XmlNameTable](./xmlnametable/) monothread. |
| [XmlAttribute](./xmlattribute/) | Représente un attribut. Les valeurs valides et par défaut de l'attribut sont définies dans une définition de type de document (DTD) ou un schéma. |
| [XmlAttributeCollection](./xmlattributecollection/) | Représente une collection d'attributs pouvant être accédés par nom ou index. |
| [XmlCDataSection](./xmlcdatasection/) | Représente une section CDATA. |
| [XmlCharacterData](./xmlcharacterdata/) | Fournit des méthodes de manipulation de texte utilisées par plusieurs classes. |
| [XmlCharType](./xmlchartype/) | À des fins internes. N'utilisez pas directement cette classe. |
| [XmlComment](./xmlcomment/) | Représente le contenu d'un commentaire XML. |
| [XmlConvert](./xmlconvert/) | Encode et décode les noms XML, et fournit des méthodes pour convertir entre les types d'exécution et les types du langage de définition XML [Schema](../system.xml.schema/) (XSD). Lors de la conversion des types de données, les valeurs retournées sont indépendantes de la locale. |
| [XmlDeclaration](./xmldeclaration/) | Représente le nœud de déclaration XML **<?xml version='1.0'...?>**. |
| [XmlDocument](./xmldocument/) | Représente un document XML. Vous pouvez utiliser cette classe pour charger, valider, modifier, ajouter et positionner du XML dans un document. |
| [XmlDocumentFragment](./xmldocumentfragment/) | Représente un objet léger utile pour les opérations d'insertion d'arbre. |
| [XmlDocumentType](./xmldocumenttype/) | Représente la déclaration de type de document. |
| [XmlElement](./xmlelement/) | Représente un élément. |
| [XmlEntity](./xmlentity/) | Représente une déclaration d'entité, telle que **<!ENTITY... >**. |
| [XmlEntityReference](./xmlentityreference/) | Représente un nœud de référence d'entité. |
| [XmlImplementation](./xmlimplementation/) | Définit le contexte pour un ensemble d'objets [XmlDocument](./xmldocument/). |
| [XmlLinkedNode](./xmllinkednode/) | Renvoie le nœud immédiatement précédent ou suivant ce nœud. |
| [XmlNamedNodeMap](./xmlnamednodemap/) | Représente une collection de nœuds pouvant être accédés par nom ou index. |
| [XmlNamespaceManager](./xmlnamespacemanager/) | Résout, ajoute et supprime des espaces de noms dans une collection et fournit la gestion du scope pour ces espaces de noms. |
| [XmlNameTable](./xmlnametable/) | Table d'objets chaîne atomisés. |
| [XmlNode](./xmlnode/) | Représente un nœud unique dans le document XML. |
| [XmlNodeChangedEventArgs](./xmlnodechangedeventargs/) | Fournit des données pour les événements **XmlDocument::NodeChanged**, **XmlDocument::NodeChanging**, **XmlDocument::NodeInserted**, **XmlDocument::NodeInserting**, **XmlDocument::NodeRemoved** et **XmlDocument::NodeRemoving**. |
| [XmlNodeList](./xmlnodelist/) | Représente une collection ordonnée de nœuds. |
| [XmlNodeReader](./xmlnodereader/) | Représente un lecteur offrant un accès rapide, non mis en cache, uniquement en avant, aux données XML dans un [XmlNode](./xmlnode/). |
| [XmlNotation](./xmlnotation/) | Représente une déclaration de notation, telle que **<!NOTATION... >**. |
| [XmlParserContext](./xmlparsercontext/) | Fournit toutes les informations de contexte requises par le [XmlReader](./xmlreader/) pour analyser un fragment XML. |
| [XmlProcessingInstruction](./xmlprocessinginstruction/) | Représente une instruction de traitement, que le XML définit pour conserver des informations spécifiques au processeur dans le texte du document. |
| [XmlQualifiedName](./xmlqualifiedname/) | Représente un nom qualifié XML. |
| [XmlReader](./xmlreader/) | Représente un lecteur offrant un accès rapide, non mis en cache, uniquement en avant, aux données XML. |
| [XmlReaderSettings](./xmlreadersettings/) | Spécifie un ensemble de fonctionnalités à prendre en charge sur l'objet [XmlReader](./xmlreader/) créé par la méthode [XmlReader::Create](./xmlreader/create/). |
| [XmlResolver](./xmlresolver/) | Résout les ressources XML externes nommées par un Uniform Resource Identifier (URI). |
| [XmlSecureResolver](./xmlsecureresolver/) | Aide à sécuriser une autre implémentation de [XmlResolver](./xmlresolver/) en enveloppant l'objet [XmlResolver](./xmlresolver/) et en limitant les ressources auxquelles le [XmlResolver](./xmlresolver/) sous-jacent a accès. |
| [XmlSignificantWhitespace](./xmlsignificantwhitespace/) | Représente l'espace blanc entre le balisage dans un nœud à contenu mixte ou l'espace blanc à l'intérieur d'un scope **xml:space='preserve'**. Cela est également appelé espace blanc significatif. |
| [XmlText](./xmltext/) | Représente le contenu textuel d'un élément ou d'un attribut. |
| [XmlTextReader](./xmltextreader/) | Représente un lecteur offrant un accès rapide, non mis en cache, uniquement en avant, aux données XML. |
| [XmlTextWriter](./xmltextwriter/) | Représente un écrivain offrant une méthode rapide, non mise en cache, uniquement en avant, pour générer des flux ou des fichiers contenant des données XML conformes à la recommandation W3C Extensible Markup Language (XML) 1.0 et aux espaces de noms XML. |
| [XmlUrlResolver](./xmlurlresolver/) | Résout les ressources XML externes nommées par un Uniform Resource Identifier (URI). |
| [XmlValidatingReader](./xmlvalidatingreader/) | Représente un lecteur offrant la validation de la définition de type de document (DTD), du schéma XML-Data Reduced (XDR) et du langage de définition XML [Schema](../system.xml.schema/) (XSD). |
| [XmlWhitespace](./xmlwhitespace/) | Représente l'espace blanc dans le contenu d'un élément. |
| [XmlWriter](./xmlwriter/) | Représente un écrivain offrant une méthode rapide, non mise en cache, uniquement en avant, pour générer des flux ou des fichiers contenant des données XML. |
| [XmlWriterSettings](./xmlwritersettings/) | Spécifie un ensemble de fonctionnalités à prendre en charge sur l'objet [XmlWriter](./xmlwriter/) créé par la méthode [XmlWriter::Create](./xmlwriter/create/). |

## Fonctions

| Fonction | Description |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&, const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&) | Compare deux objets [XmlQualifiedName](./xmlqualifiedname/). |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&, const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&) | Compare deux objets [XmlQualifiedName](./xmlqualifiedname/). |

## Énumérations

| Énumération | Description |
| --- | --- |
| [ConformanceLevel](./conformancelevel/) | Spécifie le niveau de vérification d'entrée ou de sortie que les objets [XmlReader](./xmlreader/) et [XmlWriter](./xmlwriter/) effectuent. |
| [DtdProcessing](./dtdprocessing/) | Spécifie les options de traitement des DTD. L'énumération DtdProcessing est utilisée par la classe [XmlReaderSettings](./xmlreadersettings/). |
| [EntityHandling](./entityhandling/) | Spécifie comment les [XmlTextReader](./xmltextreader/) ou [XmlValidatingReader](./xmlvalidatingreader/) gèrent les entités. |
| [Formatting](./formatting/) | Spécifie les options de mise en forme pour le [XmlTextWriter](./xmltextwriter/). |
| [NamespaceHandling](./namespacehandling/) | Spécifie s'il faut supprimer les déclarations d'espaces de noms en double dans le [XmlWriter](./xmlwriter/). |
| [NewLineHandling](./newlinehandling/) | Spécifie comment gérer les sauts de ligne. |
| [ReadState](./readstate/) | Spécifie l'état du lecteur. |
| [XmlTokenizedType](./xmltokenizedtype/) | Représente le type XML pour la chaîne. Cela permet de lire la chaîne comme un type XML particulier, par exemple un type de section CDATA. |
| [ValidationType](./validationtype/) | Spécifie le type de validation à effectuer. |
| [WhitespaceHandling](./whitespacehandling/) | Spécifie comment l'espace blanc est géré. |
| [WriteState](./writestate/) | Spécifie l'état du [XmlWriter](./xmlwriter/). |
| [ExceptionType](./exceptiontype/) |  |
| [XmlDateTimeSerializationMode](./xmldatetimeserializationmode/) | Spécifie comment traiter la valeur temporelle lors de la conversion entre chaîne et [DateTime](../system/datetime/). |
| [XmlNamespaceScope](./xmlnamespacescope/) | Définit le scope des espaces de noms. |
| [XmlNodeChangedAction](./xmlnodechangedaction/) | Spécifie le type de modification de nœud. |
| [XmlNodeOrder](./xmlnodeorder/) | Décrit l'ordre du document d'un nœud comparé à un second nœud. |
| [XmlNodeType](./xmlnodetype/) | Spécifie le type de nœud. |
| [XmlOutputMethod](./xmloutputmethod/) | Spécifie la méthode utilisée pour sérialiser la sortie [XmlWriter](./xmlwriter/). |
| [XmlSpace](./xmlspace/) | Spécifie le scope actuel **xml:space**. |
| [TriState](./tristate/) |  |
| [XmlStandalone](./xmlstandalone/) |  |

## Typedefs

| Typedef | Description |
| --- | --- |
| [XmlException](./xmlexception/) |  |
| [XmlNodeChangedEventHandler](./xmlnodechangedeventhandler/) | Représente la méthode qui gère les événements **XmlDocument::NodeChanged**, **XmlDocument::NodeChanging**, **XmlDocument::NodeInserted**, **XmlDocument::NodeInserting**, **XmlDocument::NodeRemoved** et **XmlDocument::NodeRemoving**. |