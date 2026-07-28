---
title: AppendAllLines()
second_title: Aspose.Slides C++ API referenciája
description: A megadott karakterlánc-gyűjteményből származó karakterláncokat a megadott kódolás használatával a megadott fájlhoz fűzi hozzá, minden karakterláncot új sorba írva. Ha a megadott fájl nem létezik, létrehozza. A fájl a karakterláncok írása után bezárásra kerül.
type: docs
weight: 1
url: /hu/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) metódus

A megadott karakterlánc-gyűjteményből származó karakterláncokat a megadott kódolás használatával a megadott fájlhoz fűzi hozzá, minden karakterláncot új sorba írva. Ha a megadott fájl nem létezik, létrehozza. A fájl a karakterláncok írása után bezárásra kerül.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A fájl elérési útja, amelyhez a karakterláncokat hozzá kell fűzni |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | A fájlba írandó karakterláncok |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó karakterkódolás |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Osztály [String](../../../system/string/)
* Osztály [IEnumerable](../../../system.collections.generic/ienumerable/)
* Osztály [File](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)