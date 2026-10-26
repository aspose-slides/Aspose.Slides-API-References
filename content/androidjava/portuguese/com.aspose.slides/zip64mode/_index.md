---
title: Zip64Mode
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica quando usar extensões de formato ZIP64 para arquivo OpenXML.
type: docs
url: /pt/com.aspose.slides/zip64mode/
---
**Herança:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Especifica quando usar extensões de formato ZIP64 para arquivo OpenXML.

--------------------

Arquivo OpenXML é um arquivo ZIP que tem um limite de 4 GB (2^32 bytes) para tamanho não comprimido de um arquivo, tamanho comprimido de um arquivo e tamanho total do arquivo, bem como um limite de 65 535 (2^16-1) arquivos no arquivo. Extensões de formato ZIP64 aumentam os limites para 2^64.
## Campos

| Campo | Descrição |
| --- | --- |
| [Never](#Never) | Não use extensões de formato ZIP64. |
| [IfNecessary](#IfNecessary) | Use extensões de formato ZIP64 se necessário. |
| [Always](#Always) | Sempre use extensões de formato ZIP64. |
### Never {#Never}
```
public static final int Never
```


Não use extensões de formato ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```


Use extensões de formato ZIP64 se necessário.

### Always {#Always}
```
public static final int Always
```


Sempre use extensões de formato ZIP64.