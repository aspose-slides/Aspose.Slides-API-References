---
title: Zip64Mode
second_title: Aspose.Slides pour Android via la référence API Java
description: Spécifie quand utiliser les extensions de format ZIP64 pour le fichier OpenXML.
type: docs
url: /fr/com.aspose.slides/zip64mode/
---
**Héritage :**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Spécifie quand utiliser les extensions de format ZIP64 pour le fichier OpenXML.

--------------------

Le fichier OpenXML est une archive ZIP qui possède une limite de 4 GB (2^32 bytes) sur la taille non compressée d’un fichier, la taille compressée d’un fichier et la taille totale de l’archive, ainsi qu’une limite de 65 535 (2^16-1) fichiers dans l’archive. Les extensions de format ZIP64 augmentent les limites à 2^64.
## Champs

| Champ | Description |
| --- | --- |
| [Never](#Never) | Ne pas utiliser les extensions de format ZIP64. |
| [IfNecessary](#IfNecessary) | Utiliser les extensions de format ZIP64 si nécessaire. |
| [Always](#Always) | Toujours utiliser les extensions de format ZIP64. |
### Never {#Never}
```
public static final int Never
```

Ne pas utiliser les extensions de format ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Utiliser les extensions de format ZIP64 si nécessaire.

### Always {#Always}
```
public static final int Always
```

Toujours utiliser les extensions de format ZIP64.