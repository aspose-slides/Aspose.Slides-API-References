---
title: Create()
second_title: Aspose.Slides pro C++ API referenci
description: Vytvoří nový soubor (nebo přepíše existující) a otevře jej pro čtení i zápis pomocí zadané velikosti vyrovnávací paměti a možností.
type: docs
weight: 53
url: /cs/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) metoda


Vytvoří nový soubor (nebo přepíše existující) a otevře jej pro čtení a zápis pomocí zadané velikosti vyrovnávací paměti a možností.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, který se má vytvořit nebo přepsat |
| bufferSize | **int32_t** | Počet bajtů ukládaných do vyrovnávací paměti při čtení a zápisu souboru |
| options | [FileOptions](../../fileoptions/) | Určuje, jak vytvořit nebo přepsat soubor |

### Návratová hodnota

Sdílený ukazatel na objekt [FileStream](../../filestream/) spojený se zadaným souborem

## Viz také

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)