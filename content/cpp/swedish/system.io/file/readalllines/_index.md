---
title: ReadAllLines()
second_title: Aspose.Slides för C++ API-referens
description: Läser innehållet i den angivna textfilen rad för rad till en array av strängar med den angivna teckenkodningen.
type: docs
weight: 300
url: /sv/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) metod

Läser innehållet i den angivna textfilen rad för rad till en array av strängar med den angivna teckenkodningen.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som ska läsas |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Teckenkodningen som ska användas |

### Returvärde

En strängarray där varje element representerar en enskild rad från den angivna filen

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klass [String](../../../system/string/)
* Klass [File](../)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)