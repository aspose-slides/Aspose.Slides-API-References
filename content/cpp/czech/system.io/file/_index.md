---
title: File
second_title: Aspose.Slides pro C++ referenční příručka API
description: Poskytuje metody pro manipulaci se soubory. Jedná se o statický typ bez instančních služeb. Nikdy byste ho neměli nijak vytvářet.
type: docs
weight: 261
url: /cs/system.io/file/
---
## File třída

Provides methods for manipulating files. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class File
```

## Metody

| Metoda | Popis |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Přidá řetězce ze zadané kolekce řetězců do zadaného souboru pomocí zadaného kódování tím, že každý řetězec zapíše na nový řádek. Pokud zadaný soubor neexistuje, je vytvořen. Soubor je uzavřen po zapsání všech řetězců. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Přidá zadaný řetězec do zadaného souboru pomocí zadaného kódování. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Vytvoří objekt [StreamWriter](../streamwriter/), který přidává text do zadaného souboru pomocí kódování UTF-8. Pokud zadaný soubor neexistuje, je vytvořen. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Zkopíruje zadaný soubor na zadané místo. Pokud cílový soubor již existuje, parametr určuje, zda má být přepsán. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Vytvoří nový soubor (nebo přepíše existující) a otevře jej pro čtení a zápis s použitím zadané velikosti vyrovnávací paměti a možností. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Vytvoří nový nebo otevře existující soubor pro zápis textu kódovaného UTF-8. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NEIMPLEMENTOVÁNO. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Odstraní zadaný soubor nebo adresář. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NEIMPLEMENTOVÁNO. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Určuje, zda zadaná cesta odkazuje na existující soubor. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Vrací atributy zadané entity. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Vrací čas vytvoření zadané entity jako místní čas. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Vrací čas vytvoření zadané entity jako UTC čas. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Vrací čas posledního přístupu k zadané entitě jako místní čas. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Vrací čas posledního přístupu k zadané entitě jako UTC čas. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Vrací čas posledního zápisu zadané entity jako místní čas. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Vrací čas posledního zápisu zadané entity jako UTC čas. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Přesune zadaný soubor na nové místo. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Otevře zadaný soubor ve zvoleném režimu pro čtení a zápis bez sdílení. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Otevře zadaný soubor ve zvoleném režimu, se zvoleným typem přístupu a možností sdílení. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Otevře zadaný soubor pouze pro čtení, v režimu 'Open' se sdíleným přístupem pro čtení. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Otevře existující zadaný soubor pro čtení textu pomocí kódování UTF-8 bez sdílení. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Otevře zadaný soubor pouze pro zápis, v režimu 'OpenOrCreate' bez sdílení. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Načte obsah zadaného binárního souboru do pole bajtů. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Načte obsah zadaného textového souboru řádek po řádku do pole řetězců pomocí zadaného znakového kódování. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Načte obsah zadaného textového souboru do jediného objektu [String](../../system/string/) pomocí zadaného znakového kódování. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Načte obsah zadaného textového souboru řádek po řádku pomocí zadaného znakového kódování a vrátí výčtovou kolekci řetězců, z nichž každý představuje jeden řádek obsahu souboru. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Nahradí obsah jednoho souboru jiným a vytvoří zálohu nahrazeného souboru. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Nastaví zadané atributy na zadaný soubor. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NEIMPLEMENTOVÁNO. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NEIMPLEMENTOVÁNO. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NEIMPLEMENTOVÁNO. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NEIMPLEMENTOVÁNO. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Nastaví čas posledního zápisu zadané entity jako místní čas. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Nastaví čas posledního zápisu zadané entity jako UTC čas. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Přepíše zadaný binární soubor a zapíše do něj zadané bajty. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Vytvoří nový textový soubor nebo přepíše existující a zapíše do něj všechny řetězce ze zadané výčtové kolekce řetězců, každý řetězec na nový řádek, pomocí zadaného kódování. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Vytvoří nový textový soubor nebo přepíše existující a zapíše do něj všechny řetězce ze zadaného pole řetězců, každý řetězec na nový řádek, pomocí zadaného kódování. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Vytvoří nový textový soubor nebo přepíše existující a zapíše jeho obsah ze zadaného řetězce do souboru pomocí zadaného kódování. |

## Pole

| Pole | Popis |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Výchozí hodnota počtu bajtů bufferovaných během čtení ze souboru a zápisu do souboru. |

## Viz také

* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)