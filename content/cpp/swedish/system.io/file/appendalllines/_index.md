---
title: AppendAllLines()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till strängar från den angivna samlingen av strängar till den angivna filen med den angivna kodningen genom att skriva varje sträng på en ny rad. Om den angivna filen inte finns skapas den. Filen stängs efter att alla strängar har skrivits.
type: docs
weight: 1
url: /sv/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) metod

Lägger till strängar från den angivna samlingen av strängar till den angivna filen med den angivna kodningen genom att skriva varje sträng på en ny rad. Om den angivna filen inte finns, skapas den. Filen stängs efter att alla strängar har skrivits.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till filen som strängarna ska läggas till i |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Strängarna som ska skrivas till filen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Teckenkodning att använda |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klass [String](../../../system/string/)
* Klass [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klass [File](../)
* Namnområde [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)