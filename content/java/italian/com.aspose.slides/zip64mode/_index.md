---
title: Zip64Mode
second_title: Riferimento API di Aspose.Slides per Java
description: Specifica quando utilizzare le estensioni del formato ZIP64 per un file OpenXML.
type: docs
url: /it/com.aspose.slides/zip64mode/
---
**Eredità:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Specifica quando utilizzare le estensioni del formato ZIP64 per un file OpenXML.

--------------------

Un file OpenXML è un archivio ZIP che ha un limite di 4 GB (2^32 byte) per la dimensione non compressa di un file, la dimensione compressa di un file e la dimensione totale dell'archivio, oltre a un limite di 65.535 (2^16-1) file nell'archivio. Le estensioni del formato ZIP64 aumentano i limiti a 2^64.

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


Sempre utilizzare le estensioni del formato ZIP64.