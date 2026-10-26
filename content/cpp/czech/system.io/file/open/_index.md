---
title: Open()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Otevře zadaný soubor ve zvoleném režimu pro čtení a zápis a bez sdílení.
type: docs
weight: 235
url: /cs/system.io/file/open/
---
## File::Open(const String\&, FileMode) metoda

Otevře zadaný soubor ve zvoleném režimu pro čtení i zápis a bez sdílení.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, který se má otevřít |
| mode | [FileMode](../../filemode/) | Určuje režim, ve kterém se má soubor otevřít |

### Návratová hodnota

Objekt [FileStream](../../filestream/) spojený s otevřeným souborem

## File::Open(const String\&, FileMode, FileAccess, FileShare) metoda

Otevře zadaný soubor ve zvoleném režimu, s určeným typem přístupu a možností sdílení.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, který se má otevřít |
| mode | [FileMode](../../filemode/) | Určuje režim, ve kterém se má soubor otevřít |
| access | [FileAccess](../../fileaccess/) | Požadovaný typ přístupu |
| share | [FileShare](../../fileshare/) | Typ přístupu, který mají ostatní objekty [FileStream](../../filestream/) k otevřenému souboru |

### Návratová hodnota

Objekt [FileStream](../../filestream/) spojený s otevřeným souborem

## Viz také

* Výčet [FileMode](../../filemode/)
* Výčet [FileAccess](../../fileaccess/)
* Výčet [FileShare](../../fileshare/)
* Definice typu [FileStreamPtr](../../../system/filestreamptr/)
* Třída [String](../../../system/string/)
* Třída [File](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)