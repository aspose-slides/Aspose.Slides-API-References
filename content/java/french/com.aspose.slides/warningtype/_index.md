---
title: WarningType
second_title: Référence de l'API Aspose.Slides pour Java
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
## Fields

| Field | Description |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Un problème a été détecté dans le document source, ce qui rend très probable que le document ne pourra pas être ouvert s'il est enregistré dans son format original. |
| [DataLoss](#DataLoss) | Le texte/le graphique/l'image ou d'autres données seront complètement absents soit de l'arbre du document après le chargement, soit du document créé après l'enregistrement. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Perte de mise en forme majeure. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Perte de mise en forme mineure. |
| [CompatibilityIssue](#CompatibilityIssue) | C'est un problème connu qui empêchera le document d'être ouvert par certains agents utilisateurs, ou par des versions antérieures d'agents utilisateurs. |
| [UnexpectedContent](#UnexpectedContent) | Certain contenu du document source n'a pas pu être reconnu (c.-à-d. |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

Un problème a été détecté dans le document source, ce qui rend très probable que le document ne pourra pas être ouvert s'il est enregistré dans son format original.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

Le texte/le graphique/l'image ou d'autres données seront complètement absents soit de l'arbre du document après le chargement, soit du document créé après l'enregistrement.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Perte de mise en forme majeure.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Perte de mise en forme mineure.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

C'est un problème connu qui empêchera le document d'être ouvert par certains agents utilisateurs, ou par des versions antérieures d'agents utilisateurs.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Certain contenu du document source n'a pas pu être reconnu (c.-à-d.), cela peut ou non entraîner des problèmes ou entraîner une perte de données/mise en forme.