---
title: ReadLines()
second_title: Aspose.Slides för C++ API-referens
description: Läser innehållet i den angivna textfilen rad för rad med den angivna teckenkodningen och returnerar en uppräkningsbar samling av strängar där varje sträng representerar en enskild rad i filens innehåll.
type: docs
weight: 326
url: /sv/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) metod


Läser innehållet i den angivna textfilen rad för rad med den angivna teckenkodningen och returnerar en uppräkningsbar samling av strängar där varje sträng representerar en enskild rad i filens innehåll.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som ska läsas |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Teckenkodningen som ska användas |

### Returvärde

En uppräkningsbar samling av strängar som representerar innehållet i den angivna filen

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Typdefinition [EncodingPtr](../../../system/encodingptr/)
* Klass [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klass [String](../../../system/string/)
* Klass [File](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)