---
title: FileStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van de FileStream klasse en initialiseert deze met de opgegeven parameters.
type: docs
weight: 1
url: /nl/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) constructor


Construeert een nieuw exemplaar van de [FileStream](../) klasse en initialiseert deze met de opgegeven parameters.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het te openen bestand. |
| mode | [FileMode](../../filemode/) | Specificeert de modus waarin het bestand moet worden geopend. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) constructor


Construeert een nieuw exemplaar van de [FileStream](../) klasse en initialiseert deze met de opgegeven parameters.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het te openen bestand. |
| mode | [FileMode](../../filemode/) | Specificeert de modus waarin het bestand moet worden geopend. |
| access | [FileAccess](../../fileaccess/) | Het aangevraagde toegangstype. |
| share | [FileShare](../../fileshare/) | Het type toegang dat andere [FileStream](../) objecten hebben tot het geopende bestand. |
| buffer_size | **int32_t** | Het aantal bytes dat wordt gebufferd tijdens lees- en schrijfoperaties. |
| options | [FileOptions](../../fileoptions/) | Extra opties. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) constructor


Construeert een nieuw exemplaar van de [FileStream](../) klasse en initialiseert deze met de opgegeven parameters.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad van het te openen bestand. |
| mode | [FileMode](../../filemode/) | Specificeert de modus waarin het bestand moet worden geopend. |
| access | [FileAccess](../../fileaccess/) | Het aangevraagde toegangstype. |
| share | [FileShare](../../fileshare/) | Het type toegang dat andere [FileStream](../) objecten hebben tot het geopende bestand. |
| buffer_size | **int32_t** | Het aantal bytes dat wordt gebufferd tijdens lees- en schrijfoperaties. |
| useAsync | **bool** | Specificeert of asynchrone I/O of synchrone I/O moet worden gebruikt. |
## Opmerkingen



Het onderliggende besturingssysteem ondersteunt mogelijk geen asynchrone I/O. 

## FileStream::FileStream(const FileStream\&) constructor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Zie ook

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Klasse [String](../../../system/string/)
* Klasse [FileStream](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)