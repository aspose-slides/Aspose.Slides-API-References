---
title: Create()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny fil (eller skriver över befintlig) och öppnar den för läs- och skrivåtkomst med den angivna buffertstorleken och alternativen.
type: docs
weight: 53
url: /sv/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) metod


Skapar en ny fil (eller skriver över befintlig) och öppnar den för läs- och skrivåtkomst med den angivna buffertstorleken och alternativen.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som ska skapas eller skrivas över |
| bufferSize | **int32_t** | Antalet byte som buffras vid läsning från och skrivning till filen |
| options | [FileOptions](../../fileoptions/) | Anger hur filen ska skapas eller skrivas över |

### Returvärde

En delad pekare till [FileStream](../../filestream/)-objektet som är associerat med den angivna filen

## Se även

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Klass [String](../../../system/string/)
* Klass [File](../)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)