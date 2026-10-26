---
title: Open()
second_title: Aspose.Slides voor C++ API-referentie
description: Opent het opgegeven bestand in de opgegeven modus voor lezen en schrijven zonder delen.
type: docs
weight: 235
url: /nl/system.io/file/open/
---
## File::Open(const String\&, FileMode) method

Opent het opgegeven bestand in de opgegeven modus voor lezen en schrijven zonder delen.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het te openen bestand |
| mode | [FileMode](../../filemode/) | Geeft de modus op waarmee het bestand moet worden geopend |

### Return Value

A [FileStream](../../filestream/) object associated with the opened file

## File::Open(const String\&, FileMode, FileAccess, FileShare) method

Opent het opgegeven bestand in de opgegeven modus, met het opgegeven toegangstype en deeloptie.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het te openen bestand |
| mode | [FileMode](../../filemode/) | Geeft de modus op waarmee het bestand moet worden geopend |
| access | [FileAccess](../../fileaccess/) | Het aangevraagde toegangstype |
| share | [FileShare](../../fileshare/) | Het type toegang dat andere [FileStream](../../filestream/) objecten hebben tot het geopende bestand |

### Return Value

A [FileStream](../../filestream/) object associated with the opened file

## See Also

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)