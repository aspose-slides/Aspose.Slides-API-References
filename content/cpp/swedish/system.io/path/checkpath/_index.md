---
title: CheckPath()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om den specificerade sökvägen är giltig genom att kontrollera om den innehåller ogiltiga tecken. Ett undantag kastas om sökvägen innehåller ogiltiga tecken.
type: docs
weight: 209
url: /sv/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) metod

Avgör om den specificerade sökvägen är giltig genom att kontrollera om den innehåller ogiltiga tecken. Ett undantag kastas om sökvägen innehåller ogiltiga tecken.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Sökvägen som ska kontrolleras |
| msg | const [String](../../../system/string/)\& | Meddelandet som ska skickas till undantagsobjektets konstruktor |
| allow_empty | **bool** | Anger huruvida en tom eller null-sträng ska betraktas som en korrekt sökväg (true) eller inte (false); om denna parameter är false och **path** är tomt kastas ett ArgumentException; om denna parameter är false och **path** är null kastas ett ArgumentNullException |

## Se även

* Klass [String](../../../system/string/)
* Klass [Path](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)