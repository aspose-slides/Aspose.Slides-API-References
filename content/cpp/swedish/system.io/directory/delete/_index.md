---
title: Delete()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort den angivna filen eller katalogen. Kastar inte undantag.
type: docs
weight: 14
url: /sv/system.io/directory/delete/
---
## Directory::Delete(const String\&, bool) metod


Tar bort den angivna filen eller katalogen. Kastar inte undantag.

```cpp
static void System::IO::Directory::Delete(const String &path, bool recursive=false)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen till katalogen eller filen som ska tas bort |
| recursive | **bool** | Om **path** anger en icke-tom katalog betyder **recursive** att om hela katalogens innehåll ska tas bort rekursivt; om katalogen som anges av **path** inte är tom och **recursive** är 'false' så misslyckas operationen |

## Se även

* Klass [String](../../../system/string/)
* Klass [Directory](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)