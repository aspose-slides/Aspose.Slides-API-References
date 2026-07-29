---
title: OpenText()
second_title: Aspose.Slides för C++ API-referens
description: Öppnar den angivna befintliga filen för läsning av text med UTF-8-kodning utan delning.
type: docs
weight: 261
url: /sv/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) metod


Öppnar den angivna befintliga filen för läsning av text med UTF-8-kodning utan delning.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som ska öppnas |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Teckenkodningen att använda |

### Returvärde

En delad pekare till ett [StreamWriter](../../streamwriter/)-objekt som är associerat med den öppnade filen

## Se även

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klass [String](../../../system/string/)
* Klass [File](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)