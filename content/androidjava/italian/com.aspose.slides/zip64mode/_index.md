---
title: Zip64Mode
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Specifica quando utilizzare le estensioni del formato ZIP64 per il file OpenXML.
type: docs
url: /it/com.aspose.slides/zip64mode/
---
**Ereditarietà:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Specifica quando utilizzare le estensioni del formato ZIP64 per il file OpenXML.

--------------------

Il file OpenXML è un archivio ZIP che ha un limite di 4 GB (2^32 byte) sulla dimensione non compressa di un file, sulla dimensione compressa di un file e sulla dimensione totale dell'archivio, nonché un limite di 65,535 (2^16-1) file nell'archivio. Le estensioni del formato ZIP64 aumentano i limiti a 2^64.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Never](#Never) | Non utilizzare le estensioni del formato ZIP64. |
| [IfNecessary](#IfNecessary) | Utilizzare le estensioni del formato ZIP64 se necessario. |
| [Always](#Always) | Utilizzare sempre le estensioni del formato ZIP64. |
### Never {#Never}
```
public static final int Never
```

Non utilizzare le estensioni del formato ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Utilizzare le estensioni del formato ZIP64 se necessario.

### Always {#Always}
```
public static final int Always
```

Utilizzare sempre le estensioni del formato ZIP64.