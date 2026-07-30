---
title: CheckPath()
second_title: Riferimento API Aspose.Slides per C++
description: Determina se il percorso specificato è valido controllando se contiene caratteri non validi. Viene lanciata un'eccezione se il percorso contiene caratteri non validi.
type: docs
weight: 209
url: /it/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) metodo

Determina se il percorso specificato è valido controllando se contiene caratteri non validi. Viene generata un'eccezione se il percorso contiene caratteri non validi.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso da verificare |
| msg | const [String](../../../system/string/)\& | Il messaggio da passare al costruttore dell'oggetto eccezione |
| allow_empty | **bool** | Specifica se una stringa vuota o null deve essere considerata un percorso corretto (true) o no (false); se questo parametro è false e **path** è vuoto viene generata un'ArgumentException; se questo parametro è false e **path** è null viene generata un'ArgumentNullException |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [Path](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)