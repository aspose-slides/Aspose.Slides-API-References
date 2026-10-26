---
title: CheckPath()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda je zadaná cesta platná kontrolou, zda neobsahuje neplatné znaky. Je vyvolána výjimka, pokud cesta obsahuje neplatné znaky.
type: docs
weight: 209
url: /cs/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) metoda


Určuje, zda je zadaná cesta platná kontrolou, zda neobsahuje neplatné znaky. Je vyvolána výjimka, pokud cesta obsahuje neplatné znaky.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta, která se má zkontrolovat |
| msg | const [String](../../../system/string/)\& | Zpráva, která se předá konstruktoru objektu výjimky |
| allow_empty | **bool** | Určuje, zda by měl být prázdný nebo nulový řetězec považován za správnou cestu (true) nebo ne (false); pokud je tento parametr false a **path** je prázdný, je vyvolána ArgumentException; pokud je tento parametr false a **path** je null, je vyvolána ArgumentNullException |

## Viz také

* Třída [String](../../../system/string/)
* Třída [Path](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)