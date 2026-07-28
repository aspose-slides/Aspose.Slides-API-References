---
title: WriteAllLines()
second_title: Aspose.Slides C++ API referencia
description: Új szöveges fájlt hoz létre, vagy felülírja a meglévőt, és a megadott enumerable karakterlánc-gyűjteményből az összes karakterláncot a fájlba írja, minden karakterláncot új sorba, a megadott kódolás használatával.
type: docs
weight: 456
url: /hu/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) metódus

Új szöveges fájlt hoz létre, vagy felülírja a meglévőt, és a megadott enumerable karakterlánc-gyűjteményből az összes karakterláncot beleírja a fájlba, minden karakterláncot új sorba, a megadott kódolás használatával.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A fájl, amelyet létre kell hozni vagy felülírni |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Egy enumerable karakterlánc-gyűjtemény |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó karakterkódolás |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) metódus

Új szöveges fájlt hoz létre, vagy felülírja a meglévőt, és a megadott karakterlánc tömbből az összes karakterláncot beleírja a fájlba, minden karakterláncot új sorba, a megadott kódolás használatával.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A fájl, amelyet létre kell hozni vagy felülírni |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Egy karakterlánc tömb |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó karakterkódolás |

## Kapcsolódó

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [EncodingPtr](../../../system/encodingptr/)
* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [IEnumerable](../../../system.collections.generic/ienumerable/)
* Osztály [File](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)