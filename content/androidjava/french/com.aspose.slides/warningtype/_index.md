---
title: WarningType
second_title: Référence API Aspose.Slides pour Android via Java
description: Représente un type d'avertissement.
type: docs
url: /fr/com.aspose.slides/warningtype/
---
**Héritage :**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Représente un type d'avertissement.
## Champs

| Champ | Description |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Un problème a été détecté dans le document source, ce qui rend très probable que le document ne puisse pas être ouvert s'il est enregistré dans son format original. |
| [DataLoss](#DataLoss) | Le texte, le graphique, l'image ou d'autres données seront complètement absents soit de l'arbre du document après le chargement, soit du document créé après l'enregistrement. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Perte majeure de mise en forme. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Perte mineure de mise en forme. |
| [CompatibilityIssue](#CompatibilityIssue) | Il s'agit d'un problème connu qui empêchera le document d'être ouvert par certains agents utilisateurs, ou par des versions antérieures d'agents utilisateurs. |
| [UnexpectedContent](#UnexpectedContent) | Certains contenus du document source n'ont pas pu être reconnus (c'est-à-dire |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

Un problème a été détecté dans le document source, ce qui rend très probable que le document ne puisse pas être ouvert s'il est enregistré dans son format original.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

Le texte, le graphique, l'image ou d'autres données seront complètement absents soit de l'arbre du document après le chargement, soit du document créé après l'enregistrement.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Perte majeure de mise en forme.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Perte mineure de mise en forme.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Il s'agit d'un problème connu qui empêchera le document d'être ouvert par certains agents utilisateurs, ou par des versions antérieures d'agents utilisateurs.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Certains contenus du document source n'ont pas pu être reconnus (c'est-à-dire, ils ne sont pas pris en charge), ce qui peut ou non entraîner des problèmes ou entraîner une perte de données/mise en forme.