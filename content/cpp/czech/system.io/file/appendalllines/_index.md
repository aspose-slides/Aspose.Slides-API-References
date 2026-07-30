---
title: AppendAllLines()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přidá řetězce ze zadané kolekce řetězců do určeného souboru pomocí zadaného kódování tak, že každý řetězec zapíše na nový řádek. Pokud určený soubor neexistuje, bude vytvořen. Soubor je po zapsání všech řetězců uzavřen.
type: docs
weight: 1
url: /cs/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) metoda

Přidá řetězce z určené kolekce řetězců do určeného souboru pomocí určeného kódování tak, že každý řetězec zapíše na nový řádek. Pokud určený soubor neexistuje, bude vytvořen. Soubor je po zapsání všech řetězců uzavřen.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, do kterého se mají řetězce připojit |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Řetězce, které se mají zapsat do souboru |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování znaků, které se má použít |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Třída [String](../../../system/string/)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Třída [File](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)