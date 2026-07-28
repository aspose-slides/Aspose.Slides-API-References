---
title: CheckPath()
second_title: Aspose.Slides C++ API Referencia
description: Megállapítja, hogy a megadott útvonal érvényes-e, azáltal hogy ellenőrzi, tartalmaz-e érvénytelen karaktereket. Kivétel kerül dobásra, ha az útvonal érvénytelen karaktereket tartalmaz.
type: docs
weight: 209
url: /hu/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) metódus

Megállapítja, hogy a megadott útvonal érvényes-e azáltal, hogy ellenőrzi, tartalmaz-e érvénytelen karaktereket. Kivétel kerül dobásra, ha az útvonal érvénytelen karaktereket tartalmaz.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Az ellenőrzendő útvonal |
| msg | const [String](../../../system/string/)\& | Az üzenet, amelyet az exception objektum konstruktorának kell átadni |
| allow_empty | **bool** | Megadja, hogy egy üres vagy null értékű karakterláncot helyes útvonalnak tekintsünk-e (true) vagy sem (false); ha ez a paraméter false, és a **path** üres, akkor ArgumentException kerül dobásra; ha ez a paraméter false, és a **path** null, akkor ArgumentNullException kerül dobásra |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [Path](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)