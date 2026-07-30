---
title: Copy()
second_title: Aspose.Slides – referenční příručka API pro C++
description: Zkopíruje zadaný soubor na určené místo. Pokud cílový soubor již existuje, parametr určuje, zda má být přepsán.
type: docs
weight: 40
url: /cs/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) metoda


Zkopíruje zadaný soubor na zadané místo. Pokud cílový soubor již existuje, parametr určuje, zda má být přepsán.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Cesta k souboru, který se má zkopírovat |
| destFileName | const [String](../../../system/string/)\& | Cesta k novému umístění souboru, který se má zkopírovat |
| overwrite | **bool** | True pokud má být existující cílový soubor přepsán, false pokud má kopírování selhat, když cílový soubor již existuje |

## Viz také

* Třída [String](../../../system/string/)
* Třída [File](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)