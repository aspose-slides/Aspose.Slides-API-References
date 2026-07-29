---
title: Replace()
second_title: Aspose.Slides för C++ API-referens
description: Ersätter innehållet i en specificerad destinationsfil med den fil som representeras av det aktuella FileInfo-objektet och skapar en säkerhetskopia av den ersatta filen.
type: docs
weight: 131
url: /sv/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) metod


Ersätter innehållet i en specificerad destinationsfil med filen som representeras av det aktuella [FileInfo](../)-objektet och skapar en säkerhetskopia av den ersatta filen.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Ett namn på filen som ska ersättas |
| destinationBackupFileName | const [String](../../../system/string/)\& | Ett namn på säkerhetskopian |

### Return Value

Ett FileInfor-objekt som representerar filen som pekas på av **destinationFileName**

## FileInfo::Replace(const String\&, const String\&, bool) metod


Ersätter innehållet i en specificerad destinationsfil med filen som representeras av det aktuella [FileInfo](../)-objektet och skapar en säkerhetskopia av den ersatta filen.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Ett namn på filen som ska ersättas |
| destinationBackupFileName | const [String](../../../system/string/)\& | Ett namn på säkerhetskopian |
| ignoreMetadataErrors | **bool** | Anger om sammanfogningsfelen från den ersatta filen till ersättningsfilen ska ignoreras (true) eller inte (false) |

### Return Value

Ett FileInfor-objekt som representerar filen som pekas på av **destinationFileName**

## See Also

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)