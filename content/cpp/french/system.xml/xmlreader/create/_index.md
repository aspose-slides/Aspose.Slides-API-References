---
title: Create()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle instance XmlReader avec l'URI spécifié.
type: docs
weight: 1015
url: /fr/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) method

Crée une nouvelle instance [XmlReader](../) avec l'URI spécifié.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L'URI du fichier contenant les données XML. La classe [XmlUrlResolver](../../xmlurlresolver/) est utilisée pour convertir le chemin en une représentation canonique des données. |

### Valeur de retour

Un objet utilisé pour lire les données XML dans le flux.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) method

Crée une nouvelle instance [XmlReader](../) en utilisant l'URI et les paramètres spécifiés.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L'URI du fichier contenant les données XML. L'objet [XmlResolver](../../xmlresolver/) sur l'objet [XmlReaderSettings](../../xmlreadersettings/) est utilisé pour convertir le chemin en une représentation canonique des données. Si la valeur XmlReaderSettings::get_XmlResolver est **nullptr**, un objet [XmlUrlResolver](../../xmlurlresolver/) est utilisé. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Les paramètres pour la nouvelle instance [XmlReader](../). Cette valeur peut être **nullptr**. |

### Valeur de retour

Un objet utilisé pour lire les données XML dans le flux.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method

Crée une nouvelle instance [XmlReader](../) en utilisant l'URI, les paramètres et les informations de contexte de l’analyse.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L'URI du fichier contenant les données XML. L'objet [XmlResolver](../../xmlresolver/) sur l'objet [XmlReaderSettings](../../xmlreadersettings/) est utilisé pour convertir le chemin en une représentation canonique des données. Si la valeur XmlReaderSettings::get_XmlResolver est **nullptr**, un objet [XmlUrlResolver](../../xmlurlresolver/) est utilisé. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Les paramètres pour la nouvelle instance [XmlReader](../). Cette valeur peut être **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Les informations de contexte nécessaires à l'analyse du fragment XML. Le contexte peut inclure le [XmlNameTable](../../xmlnametable/) à utiliser, l’encodage, la portée de l’espace de noms, la portée actuelle **xml:lang** et **xml:space**, l'URI de base et la définition du type de document. Cette valeur peut être **nullptr**. |

### Valeur de retour

Un objet utilisé pour lire les données XML dans le flux.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) method

Crée une nouvelle instance [XmlReader](../) en utilisant le flux spécifié avec les paramètres par défaut.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux contenant les données XML. [XmlReader](../) analyse les premiers octets du flux à la recherche d’un marqueur d’ordre d’octet ou d’un autre indice d’encodage. Une fois l’encodage déterminé, il est utilisé pour poursuivre la lecture du flux, et le traitement poursuit l’analyse de l’entrée comme un flux de caractères (Unicode). |

### Valeur de retour

Un objet utilisé pour lire les données XML dans le flux.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) method

Crée une nouvelle instance [XmlReader](../) avec le flux et les paramètres spécifiés.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux contenant les données XML. [XmlReader](../) analyse les premiers octets du flux à la recherche d’un marqueur d’ordre d’octet ou d’un autre indice d’encodage. Une fois l’encodage déterminé, il est utilisé pour poursuivre la lecture du flux, et le traitement poursuit l’analyse de l’entrée comme un flux de caractères (Unicode). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Les paramètres pour la nouvelle instance [XmlReader](../). Cette valeur peut être **nullptr**. |

### Valeur de retour

Un objet utilisé pour lire les données XML dans le flux.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method

Crée une nouvelle instance [XmlReader](../) en utilisant le flux, l’URI de base et les paramètres spécifiés.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux contenant les données XML. [XmlReader](../) analyse les premiers octets du flux à la recherche d’un marqueur d’ordre d’octet ou d’un autre indice d’encodage. Une fois l’encodage déterminé, il est utilisé pour poursuivre la lecture du flux, et le traitement poursuit l’analyse de l’entrée comme un flux de caractères (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Les paramètres pour la nouvelle instance [XmlReader](../). Cette valeur peut être **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | L'URI de base pour l’entité ou le document lu. Cette valeur peut être **nullptr**. **[Security](../../../system.security/) Remarque** L'URI de base est utilisé pour résoudre l'URI relatif du document XML. N’utilisez pas un URI de base provenant d’une source non fiable. |

### Valeur de retour

Un objet utilisé pour lire les données XML dans le flux.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method

Crée une nouvelle instance [XmlReader](../) en utilisant le flux, les paramètres et les informations de contexte de l’analyse.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux contenant les données XML. [XmlReader](../) analyse les premiers octets du flux à la recherche d’un marqueur d’ordre d’octet ou d’un autre indice d’encodage. Une fois l’encodage déterminé, il est utilisé pour poursuivre la lecture du flux, et le traitement poursuit l’analyse de l’entrée comme un flux de caractères (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Les paramètres pour la nouvelle instance [XmlReader](../). Cette valeur peut être **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Les informations de contexte nécessaires à l'analyse du fragment XML. Le contexte peut inclure le [XmlNameTable](../../xmlnametable/) à utiliser, l’encodage, la portée de l’espace de noms, la portée actuelle **xml:lang** et **xml:space**, l'URI de base et la définition du type de document. Cette valeur peut être **nullptr**. |

### Valeur de retour

Un objet utilisé pour lire les données XML dans le flux.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) method

Crée une nouvelle instance [XmlReader](../) en utilisant le lecteur de texte spécifié.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Le lecteur de texte à partir duquel lire les données XML. Un lecteur de texte renvoie un flux de caractères Unicode, ainsi l’encodage indiqué dans la déclaration XML n’est pas utilisé par le lecteur XML pour décoder le flux de données. |

### Valeur de retour

Un objet utilisé pour lire les données XML dans le flux.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) method

Crée une nouvelle instance [XmlReader](../) en utilisant le lecteur de texte et les paramètres spécifiés.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Le lecteur de texte à partir duquel lire les données XML. Un lecteur de texte renvoie un flux de caractères Unicode, ainsi l’encodage indiqué dans la déclaration XML n’est pas utilisé par le lecteur XML pour décoder le flux de données. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Les paramètres pour le nouveau [XmlReader](../). Cette valeur peut être **nullptr**. |

### Valeur de retour

Un objet utilisé pour lire les données XML dans le flux.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method

Crée une nouvelle instance [XmlReader](../) en utilisant le lecteur de texte, les paramètres et l’URI de base spécifiés.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Le lecteur de texte à partir duquel lire les données XML. Un lecteur de texte renvoie un flux de caractères Unicode, ainsi l’encodage indiqué dans la déclaration XML n’est pas utilisé par le [XmlReader](../) pour décoder le flux de données. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Les paramètres pour la nouvelle instance [XmlReader](../). Cette valeur peut être **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | L'URI de base pour l’entité ou le document lu. Cette valeur peut être **nullptr**. **[Security](../../../system.security/) Remarque** L'URI de base est utilisé pour résoudre l'URI relatif du document XML. N’utilisez pas un URI de base provenant d’une source non fiable. |

### Valeur de retour

Un objet utilisé pour lire les données XML dans le flux.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method

Crée une nouvelle instance [XmlReader](../) en utilisant le lecteur de texte, les paramètres et les informations de contexte de l’analyse.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Le lecteur de texte à partir duquel lire les données XML. Un lecteur de texte renvoie un flux de caractères Unicode, ainsi l’encodage indiqué dans la déclaration XML n’est pas utilisé par le lecteur XML pour décoder le flux de données. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Les paramètres pour la nouvelle instance [XmlReader](../). Cette valeur peut être **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Les informations de contexte nécessaires à l'analyse du fragment XML. Le contexte peut inclure le [XmlNameTable](../../xmlnametable/) à utiliser, l’encodage, la portée de l’espace de noms, la portée actuelle **xml:lang** et **xml:space**, l'URI de base et la définition du type de document. Cette valeur peut être **nullptr**. |

### Valeur de retour

Un objet utilisé pour lire les données XML dans le flux.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) method

Crée une nouvelle instance [XmlReader](../) en utilisant le lecteur XML et les paramètres spécifiés.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | L'objet que vous souhaitez utiliser comme lecteur XML sous-jacent. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Les paramètres pour la nouvelle instance [XmlReader](../). Le niveau de conformité de l'objet [XmlReaderSettings](../../xmlreadersettings/) doit soit correspondre au niveau de conformité du lecteur sous-jacent, soit être défini sur [ConformanceLevel::Auto](../../conformancelevel/). |

### Valeur de retour

Un objet enveloppé autour de l'objet [XmlReader](../) spécifié.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Class [TextReader](../../../system.io/textreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)