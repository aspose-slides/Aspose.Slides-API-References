---
title: AppendAllText()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Připojí zadaný řetězec k určenému souboru pomocí zadaného kódování.
type: docs
weight: 14
url: /cs/system.io/file/appendalltext/
---
## File::AppendAllText(const String\&, const String\&, const EncodingPtr\&) metoda


Přidá zadaný řetězec do určeného souboru pomocí zadaného kódování.

```cpp
static void System::IO::File::AppendAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, do kterého se má řetězec připojit |
| contents | const [String](../../../system/string/)\& | Řetězec, který se má zapsat do souboru |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování znaků, které se má použít |

## Viz také

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)