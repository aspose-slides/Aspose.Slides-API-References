---
title: Create()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy új fájlt (vagy felülírja a meglévőt), és megnyitja olvasási és írási hozzáféréshez a megadott pufferméret és beállítások használatával.
type: docs
weight: 53
url: /hu/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) módszer


Létrehoz egy új fájlt (vagy felülírja a meglévőt), és megnyitja olvasási és írási hozzáféréshez a megadott pufferméret és beállítások használatával.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A fájl elérési útja, amelyet létre kell hozni vagy felülírni |
| bufferSize | **int32_t** | A bájtok száma, amely a fájl olvasásakor és írásakor pufferelésre kerül |
| options | [FileOptions](../../fileoptions/) | Megadja, hogyan hozza létre vagy írja felül a fájlt |

### Visszatérési érték

Megosztott mutató a(z) [FileStream](../../filestream/) objektumra, amely a megadott fájlhoz kapcsolódik

## Lásd még

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)