---
title: Create()
second_title: Référence API Aspose.Slides pour C++
description: Crée une nouvelle instance XmlWriter en utilisant le nom de fichier spécifié.
type: docs
weight: 469
url: /fr/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) méthode


Crée une nouvelle instance [XmlWriter](../) en utilisant le nom de fichier spécifié.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Le fichier dans lequel vous souhaitez écrire. Le [XmlWriter](../) crée un fichier au chemin spécifié et y écrit en syntaxe texte XML 1.0. **outputFileName** doit être un chemin du système de fichiers. |

### Valeur de retour

Un objet [XmlWriter](../).

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) méthode


Crée une nouvelle instance [XmlWriter](../) en utilisant le nom de fichier et l’objet [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Le fichier dans lequel vous souhaitez écrire. Le [XmlWriter](../) crée un fichier au chemin spécifié et y écrit en syntaxe texte XML 1.0. **outputFileName** doit être un chemin du système de fichiers. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | L’objet [XmlWriterSettings](../../xmlwritersettings/) utilisé pour configurer la nouvelle instance [XmlWriter](../). Si cette valeur est **nullptr**, un [XmlWriterSettings](../../xmlwritersettings/) avec les paramètres par défaut est utilisé. Si le [XmlWriter](../) est utilisé avec la méthode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), vous devez utiliser la valeur XslCompiledTransform::get_OutputSettings pour obtenir un objet [XmlWriterSettings](../../xmlwritersettings/) avec les paramètres corrects. Cela garantit que l’objet [XmlWriter](../) créé possède les paramètres de sortie appropriés. |

### Valeur de retour

Un objet [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) méthode


Crée une nouvelle instance [XmlWriter](../) en utilisant le flux spécifié.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux dans lequel vous souhaitez écrire. Le [XmlWriter](../) écrit la syntaxe texte XML 1.0 et l’ajoute au flux spécifié. |

### Valeur de retour

Un objet [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) méthode


Crée une nouvelle instance [XmlWriter](../) en utilisant le flux et l’objet [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux dans lequel vous souhaitez écrire. Le [XmlWriter](../) écrit la syntaxe texte XML 1.0 et l’ajoute au flux spécifié. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | L’objet [XmlWriterSettings](../../xmlwritersettings/) utilisé pour configurer la nouvelle instance [XmlWriter](../). Si cette valeur est **nullptr**, un [XmlWriterSettings](../../xmlwritersettings/) avec les paramètres par défaut est utilisé. Si le [XmlWriter](../) est utilisé avec la méthode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), vous devez utiliser la valeur XslCompiledTransform::get_OutputSettings pour obtenir un objet [XmlWriterSettings](../../xmlwritersettings/) avec les paramètres corrects. Cela garantit que l’objet [XmlWriter](../) créé possède les paramètres de sortie appropriés. |

### Valeur de retour

Un objet [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) méthode


Crée une nouvelle instance [XmlWriter](../) en utilisant le TextWriter spécifié.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Le TextWriter dans lequel vous souhaitez écrire. Le [XmlWriter](../) écrit la syntaxe texte XML 1.0 et l’ajoute au TextWriter spécifié. |

### Valeur de retour

Un objet [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) méthode


Crée une nouvelle instance [XmlWriter](../) en utilisant le TextWriter et les objets [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Le TextWriter dans lequel vous souhaitez écrire. Le [XmlWriter](../) écrit la syntaxe texte XML 1.0 et l’ajoute au TextWriter spécifié. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | L’objet [XmlWriterSettings](../../xmlwritersettings/) utilisé pour configurer la nouvelle instance [XmlWriter](../). Si cette valeur est **nullptr**, un [XmlWriterSettings](../../xmlwritersettings/) avec les paramètres par défaut est utilisé. Si le [XmlWriter](../) est utilisé avec la méthode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), vous devez utiliser la valeur XslCompiledTransform::get_OutputSettings pour obtenir un objet [XmlWriterSettings](../../xmlwritersettings/) avec les paramètres corrects. Cela garantit que l’objet [XmlWriter](../) créé possède les paramètres de sortie appropriés. |

### Valeur de retour

Un objet [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) méthode


Crée une nouvelle instance [XmlWriter](../) en utilisant le [Text::StringBuilder](../../../system.text/stringbuilder/) spécifié.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Le [Text::StringBuilder](../../../system.text/stringbuilder/) dans lequel écrire. Le contenu écrit par le [XmlWriter](../) est ajouté au [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Valeur de retour

Un objet [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) méthode


Crée une nouvelle instance [XmlWriter](../) en utilisant les objets [Text::StringBuilder](../../../system.text/stringbuilder/) et [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Le [Text::StringBuilder](../../../system.text/stringbuilder/) dans lequel écrire. Le contenu écrit par le [XmlWriter](../) est ajouté au [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | L’objet [XmlWriterSettings](../../xmlwritersettings/) utilisé pour configurer la nouvelle instance [XmlWriter](../). Si cette valeur est **nullptr**, un [XmlWriterSettings](../../xmlwritersettings/) avec les paramètres par défaut est utilisé. Si le [XmlWriter](../) est utilisé avec la méthode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), vous devez utiliser la valeur XslCompiledTransform::get_OutputSettings pour obtenir un objet [XmlWriterSettings](../../xmlwritersettings/) avec les paramètres corrects. Cela garantit que l’objet [XmlWriter](../) créé possède les paramètres de sortie appropriés. |

### Valeur de retour

Un objet [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) méthode


Crée une nouvelle instance [XmlWriter](../) en utilisant l’objet [XmlWriter](../) spécifié.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | L’objet [XmlWriter](../) que vous souhaitez utiliser comme writer sous-jacent. |

### Valeur de retour

Un objet [XmlWriter](../) qui enveloppe l’objet [XmlWriter](../) spécifié.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) méthode


Crée une nouvelle instance [XmlWriter](../) en utilisant les objets [XmlWriter](../) et [XmlWriterSettings](../../xmlwritersettings/) spécifiés.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | L’objet [XmlWriter](../) que vous souhaitez utiliser comme writer sous-jacent. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | L’objet [XmlWriterSettings](../../xmlwritersettings/) utilisé pour configurer la nouvelle instance [XmlWriter](../). Si cette valeur est **nullptr**, un [XmlWriterSettings](../../xmlwritersettings/) avec les paramètres par défaut est utilisé. Si le [XmlWriter](../) est utilisé avec la méthode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), vous devez utiliser la valeur XslCompiledTransform::get_OutputSettings pour obtenir un objet [XmlWriterSettings](../../xmlwritersettings/) avec les paramètres corrects. Cela garantit que l’objet [XmlWriter](../) créé possède les paramètres de sortie appropriés. |

### Valeur de retour

Un objet [XmlWriter](../) qui enveloppe l’objet [XmlWriter](../) spécifié.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlWriter](../)
* Classe [String](../../../system/string/)
* Classe [XmlWriterSettings](../../xmlwritersettings/)
* Classe [Stream](../../../system.io/stream/)
* Classe [TextWriter](../../../system.io/textwriter/)
* Classe [StringBuilder](../../../system.text/stringbuilder/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)