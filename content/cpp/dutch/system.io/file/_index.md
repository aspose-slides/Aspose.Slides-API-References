---
title: File
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt methoden voor het manipuleren van bestanden. Dit is een statisch type zonder instantiediensten. U moet onder geen enkele omstandigheid instanties ervan maken.
type: docs
weight: 261
url: /nl/system.io/file/
---
## File klasse

Biedt methoden voor het manipuleren van bestanden. Dit is een statisch type zonder instantiediensten. U moet onder geen enkele omstandigheid instanties ervan maken.

```cpp
class File
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Voegt strings toe uit de opgegeven collectie van strings naar het opgegeven bestand met de opgegeven codering door elke string in een nieuwe regel te schrijven. Als het opgegeven bestand niet bestaat, wordt het aangemaakt. Het bestand wordt gesloten nadat alle strings zijn geschreven. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Voegt de opgegeven string toe aan het opgegeven bestand met de opgegeven codering. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Creëert een [StreamWriter](../streamwriter/) object dat tekst toevoegt aan het opgegeven bestand met UTF-8 codering. Als het opgegeven bestand niet bestaat, wordt het aangemaakt. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Kopieert het opgegeven bestand naar de opgegeven locatie. Als het bestemmingsbestand al bestaat, geeft een parameter aan of het overschreven moet worden. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Creëert een nieuw bestand (of overschrijft een bestaand) en opent het voor lees- en schrijftoegang met de opgegeven buffergrootte en opties. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Creëert een nieuw of opent een bestaand bestand voor het schrijven van UTF-8 gecodeerde tekst. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NIET GEREALISEERD. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Verwijdert het opgegeven bestand of de opgegeven map. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NIET GEREALISEERD. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Bepaalt of het opgegeven pad verwijst naar een bestaand bestand. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Retourneert de attributen van de opgegeven entiteit. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Retourneert de aanmaaktijd van de opgegeven entiteit als lokale tijd. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Retourneert de aanmaaktijd van de opgegeven entiteit als UTC-tijd. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Retourneert de laatst-toegangsdatum van de opgegeven entiteit als lokale tijd. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Retourneert de laatst-toegangsdatum van de opgegeven entiteit als UTC-tijd. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Retourneert de laatst-schrijftijd van de opgegeven entiteit als lokale tijd. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Retourneert de laatst-schrijftijd van de opgegeven entiteit als UTC-tijd. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Verplaatst het opgegeven bestand naar de nieuwe locatie. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Opent het opgegeven bestand in de opgegeven modus voor lezen en schrijven zonder delen. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Opent het opgegeven bestand in de opgegeven modus, met het opgegeven toegangstype en deeloptie. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Opent het opgegeven bestand alleen voor lezen, in de modus 'Open' met gedeelde toegang voor lezen. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Opent het opgegeven bestaande bestand voor het lezen van tekst met UTF-8 codering zonder delen. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Opent het opgegeven bestand alleen voor schrijven, in de modus 'OpenOrCreate' zonder delen. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Leest de inhoud van het opgegeven binaire bestand naar een byte-array. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Leest de inhoud van het opgegeven tekstbestand regel voor regel naar een array van strings met de opgegeven tekencodering. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Leest de inhoud van het opgegeven tekstbestand naar een enkel [String](../../system/string/) object met de opgegeven tekencodering. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Leest de inhoud van het opgegeven tekstbestand regel voor regel met de opgegeven tekencodering en retourneert een doorzoekbare collectie van strings, waarbij elke string een enkele regel van de bestandsinhoud vertegenwoordigt. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Vervangt de inhoud van één bestand door een ander en maakt een backup van het vervangen bestand. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Stelt de opgegeven attributen in op het opgegeven bestand. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NIET GEREALISEERD. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NIET GEREALISEERD. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NIET GEREALISEERD. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NIET GEREALISEERD. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Stelt de laatst-schrijftijd van de opgegeven entiteit in als lokale tijd. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Stelt de laatst-schrijftijd van de opgegeven entiteit in als UTC-tijd. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Overschrijft het opgegeven binaire bestand en schrijft de opgegeven bytes erin. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Creëert een nieuw tekstbestand of overschrijft het bestaande en schrijft alle strings uit de opgegeven doorzoekbare collectie van strings erin, elke string op een nieuwe regel, met de opgegeven codering. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Creëert een nieuw tekstbestand of overschrijft het bestaande en schrijft alle strings uit de opgegeven array van strings erin, elke string op een nieuwe regel, met de opgegeven codering. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Creëert een nieuw tekstbestand of overschrijft het bestaande en schrijft de inhoud van de opgegeven string erin met de opgegeven codering. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Standaardwaarde van het aantal bytes dat gebufferd wordt tijdens het lezen van en schrijven naar een bestand. |

## Zie ook

* Namespace [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)