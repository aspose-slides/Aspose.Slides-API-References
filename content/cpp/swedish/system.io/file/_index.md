---
title: File
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller metoder för att manipulera filer. Detta är en statisk typ utan instansservice. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 261
url: /sv/system.io/file/
---
## Fil klass

Tillhandahåller metoder för att manipulera filer. Detta är en statisk typ utan instansservice. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class File
```

## Metoder

| Method | Description |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Lägger till strängar från den angivna samlingen av strängar till den angivna filen med den angivna kodningen genom att skriva varje sträng på en ny rad. Om den angivna filen inte finns skapas den. Filen stängs efter att alla strängar har skrivits. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Lägger till den angivna strängen till den angivna filen med den angivna kodningen. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Skapar ett [StreamWriter](../streamwriter/)-objekt som lägger till text till den angivna filen med UTF-8-kodning. Om den angivna filen inte finns skapas den. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Kopierar den angivna filen till den angivna platsen. Om destinationsfilen redan finns, anger en parameter om den ska skrivas över. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Skapar en ny fil (eller skriver över befintlig) och öppnar den för läs- och skrivåtkomst med den angivna buffertstorleken och alternativen. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Skapar en ny eller öppnar en befintlig fil för att skriva UTF-8-kodad text. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | INTE IMPLEMENTERAD. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Tar bort den angivna filen eller katalogen. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | INTE IMPLEMENTERAD. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Bestämmer om den angivna sökvägen refererar till en befintlig fil. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Returnerar attributen för den angivna enheten. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Returnerar skapandetiden för den angivna enheten i lokal tid. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Returnerar skapandetiden för den angivna enheten i UTC-tid. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Returnerar den senaste åtkomsttiden för den angivna enheten i lokal tid. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Returnerar den senaste åtkomsttiden för den angivna enheten i UTC-tid. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Returnerar den senaste skrivtiden för den angivna enheten i lokal tid. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Returnerar den senaste skrivtiden för den angivna enheten i UTC-tid. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Flyttar den angivna filen till den nya platsen. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Öppnar den angivna filen i det angivna läget för läs- och skrivåtkomst utan delning. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Öppnar den angivna filen i det angivna läget, med den angivna åtkomsttypen och delningsalternativet. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Öppnar den angivna filen endast för läsning, i läget 'Open' med delad åtkomst för läsning. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Öppnar den angivna befintliga filen för att läsa text med UTF-8-kodning utan delning. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Öppnar den angivna filen endast för skrivning, i läget 'OpenOrCreate' utan delning. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Läser innehållet i den angivna binära filen till en byte-array. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Läser innehållet i den angivna textfilen rad för rad till en strängarray med den angivna teckenkodningen. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Läser innehållet i den angivna textfilen till ett enda [String](../../system/string/)-objekt med den angivna teckenkodningen. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Läser innehållet i den angivna textfilen rad för rad med den angivna teckenkodningen och returnerar en uppräkningssamling av strängar där varje sträng representerar en enskild rad i filens innehåll. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Ersätter innehållet i en fil med en annan och skapar en säkerhetskopia av den ersatta filen. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Ställer in de angivna attributen på den angivna filen. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | INTE IMPLEMENTERAD. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | INTE IMPLEMENTERAD. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | INTE IMPLEMENTERAD. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | INTE IMPLEMENTERAD. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ställer in den senaste skrivtiden för den angivna enheten i lokal tid. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ställer in den senaste skrivtiden för den angivna enheten i UTC-tid. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Skriver över den angivna binära filen och skriver de angivna byten till den. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Skapar en ny textfil eller skriver över den befintliga och skriver alla strängar från den angivna uppräkningssamlingen av strängar till den, varje sträng på en ny rad, med den angivna kodningen. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Skapar en ny textfil eller skriver över den befintliga och skriver alla strängar från den angivna arrayen av strängar till den, varje sträng på en ny rad, med den angivna kodningen. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Skapar en ny textfil eller skriver över den befintliga och skriver innehållet i den angivna strängen till den med den angivna kodningen. |

## Fält

| Field | Description |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Standardvärde för antalet byte som buffras under läsning från och skrivning till en fil. |

## Se också

* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)