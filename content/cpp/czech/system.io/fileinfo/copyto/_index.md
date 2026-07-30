---
title: CopyTo()
second_title: Aspose.Slides pro C++ API Reference
description: Zkopíruje soubor reprezentovaný aktuálním objektem do určeného umístění. Pokud soubor v cíli již existuje, kopírování selže.
type: docs
weight: 105
url: /cs/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) metoda


Zkopíruje soubor reprezentovaný aktuálním objektem do určeného umístění. Pokud soubor v cíli již existuje, kopírování selže.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Název cílového souboru |

### Návratová hodnota

Objekt [FileInfo](../), který představuje kopii

## FileInfo::CopyTo(const String\&, bool) metoda


Zkopíruje soubor reprezentovaný aktuálním objektem do určeného umístění. Parametr určuje, zda má být existující soubor v cíli přepsán.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Název cílového souboru |
| overwrite | **bool** | True pokud má být existující soubor v cíli přepsán, false pokud má kopírování selhat, pokud soubor v cíli již existuje |

### Návratová hodnota

Objekt [FileInfo](../), který představuje kopii

## Viz také

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Třída [String](../../../system/string/)
* Třída [FileInfo](../)
* Jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)