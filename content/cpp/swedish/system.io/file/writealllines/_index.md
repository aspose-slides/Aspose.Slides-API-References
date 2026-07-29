---
title: WriteAllLines()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny textfil eller skriver över den befintliga och skriver alla strängar från den angivna enumererbara samlingen av strängar till den, varje sträng på en ny rad, med den angivna kodningen.
type: docs
weight: 456
url: /sv/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) metod

Skapar en ny textfil eller skriver över den befintliga och skriver alla strängar från den angivna enumererbara samlingen av strängar till den, varje sträng på en ny rad, med den angivna kodningen.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Filen att skapa eller skriva över |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | En enumererbar samling av strängar |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Teckenkodningen att använda |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) metod

Skapar en ny textfil eller skriver över den befintliga och skriver alla strängar från den angivna strängarrayen till den, varje sträng på en ny rad, med den angivna kodningen.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Filen att skapa eller skriva över |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | En strängarray |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Teckenkodningen att använda |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klass [File](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)