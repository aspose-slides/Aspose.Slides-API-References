---
title: Replace()
second_title: Aspose.Slides för C++ API-referens
description: Ersätter innehållet i en fil med en annan och skapar en säkerhetskopia av den ersatta filen.
type: docs
weight: 339
url: /sv/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) metod


Ersätter innehållet i en fil med en annan och skapar en säkerhetskopia av den ersatta filen.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Ett namn på filen att ersätta med |
| destinationFileName | const [String](../../../system/string/)\& | Ett namn på filen att ersätta |
| destinationBackupFileName | const [String](../../../system/string/)\& | Ett namn på säkerhetskopian |
| ignoreMetadataErrors | **bool** | Anger om sammanslagningsfel från den ersatta filen till ersättningsfilen ska ignoreras (true) eller inte (false) |

## Se även

* Klass [String](../../../system/string/)
* Klass [File](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)