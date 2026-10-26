---
title: File
second_title: Aspose.Slides C++ API-referencia
description: Metódusokat biztosít a fájlok kezeléséhez. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha ne hozzon létre példányt belőle semmilyen módon.
type: docs
weight: 261
url: /hu/system.io/file/
---
## File osztály

Metódusokat biztosít a fájlok kezeléséhez. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha nem szabad példányokat létrehozni belőle semmilyen módon.

```cpp
class File
```

## Metódusok

| Method | Description |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | A megadott karakterláncok gyűjteményéből származó karakterláncokat a megadott fájlhoz fűzi a megadott kódolás használatával, minden karakterláncot új sorba írva. Ha a megadott fájl nem létezik, létrehozzák. A fájl bezáródik az összes karakterlánc írása után. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | A megadott karakterláncot a megadott fájlhoz fűzi a megadott kódolás használatával. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Létrehoz egy [StreamWriter](../streamwriter/) objektumot, amely szöveget fűz a megadott fájlhoz UTF-8 kódolás használatával. Ha a megadott fájl nem létezik, létrehozzák. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | A megadott fájlt a megadott helyre másolja. Ha a célfájl már létezik, egy paraméter határozza meg, hogy felül legyen-e írva. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Új fájlt hoz létre (vagy felülírja a meglévőt), és megnyitja olvasási és írási hozzáférésre a megadott puffermérettel és beállításokkal. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Új fájlt hoz létre, vagy megnyit egy meglévő fájlt UTF-8 kódolt szöveg írásához. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NEM KIVITELESÍTETT. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | A megadott fájlt vagy könyvtárat törli. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NEM KIVITELESÍTETT. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Megállapítja, hogy a megadott útvonal egy meglévő fájlra mutat-e. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás attribútumait. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás létrehozási időpontját helyi időként. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás létrehozási időpontját UTC időként. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás utolsó hozzáférési időpontját helyi időként. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás utolsó hozzáférési időpontját UTC időként. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás utolsó írási időpontját helyi időként. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás utolsó írási időpontját UTC időként. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Áthelyezi a megadott fájlt az új helyre. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Megnyitja a megadott fájlt a megadott módban olvasáshoz és íráshoz, megosztás nélkül. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Megnyitja a megadott fájlt a megadott módban, a megadott hozzáféréstípussal és megosztási opcióval. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Megnyitja a megadott fájlt csak olvasásra, 'Open' módban, megosztott olvasási hozzáféréssel. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Megnyitja a meglévő megadott fájlt szöveg olvasására UTF-8 kódolás használatával, megosztás nélkül. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Megnyitja a megadott fájlt csak írásra, 'OpenOrCreate' módban, megosztás nélkül. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Beolvassa a megadott bináris fájl tartalmát egy bájt tömbbe. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Beolvassa a megadott szöveges fájl tartalmát soronként egy karakterlánc tömbbe a megadott karakterkódolás használatával. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Beolvassa a megadott szöveges fájl tartalmát egyetlen [String](../../system/string/) objektumba a megadott karakterkódolás használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Beolvassa a megadott szöveges fájl tartalmát soronként a megadott karakterkódolás használatával, és visszaad egy felsorolható karakterlánc-gyűjteményt, ahol minden elem a fájl egyetlen sorát jelenti. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Lecseréli egy fájl tartalmát egy másikra, és biztonsági másolatot készít a helyettesített fájlról. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Beállítja a megadott attribútumokat a megadott fájlon. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NEM KIVITELESÍTETT. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NEM KIVITELESÍTETT. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NEM KIVITELESÍTETT. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NEM KIVITELESÍTETT. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Beállítja a megadott entitás utolsó írási időpontját helyi időként. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Beállítja a megadott entitás utolsó írási időpontját UTC időként. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Felülírja a megadott bináris fájlt, és a megadott bájtokat írja bele. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Új szöveges fájlt hoz létre vagy felülírja a meglévőt, és a megadott felsorolható karakterlánc-gyűjtemény összes elemet a fájlba írja, minden karakterláncot új sorba, a megadott kódolás használatával. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Új szöveges fájlt hoz létre vagy felülírja a meglévőt, és a megadott karakterlánc tömb összes elemét a fájlba írja, minden karakterláncot új sorba, a megadott kódolás használatával. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Új szöveges fájlt hoz létre vagy felülírja a meglévőt, és a megadott karakterlánc tartalmát a fájlba írja a megadott kódolás használatával. |

## Mezők

| Field | Description |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Az alapértelmezett érték, amely a fájl olvasása és írása során pufferelt bájtok száma. |

## Lásd még

* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)