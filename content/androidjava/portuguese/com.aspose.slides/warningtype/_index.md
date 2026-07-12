---
title: WarningType
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um tipo de aviso.
type: docs
url: /pt/com.aspose.slides/warningtype/
---
**Herança:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Representa um tipo de aviso.
## Campos

| Campo | Descrição |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Foi detectado um problema no documento de origem que torna muito provável que o documento não possa ser aberto se for salvo em seu formato original. |
| [DataLoss](#DataLoss) | Texto/gráfico/imagem ou outros dados estarão completamente ausentes tanto da árvore de documentos após o carregamento quanto do documento criado após a gravação. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Grande perda de formatação. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Pequena perda de formatação. |
| [CompatibilityIssue](#CompatibilityIssue) | Este é um problema conhecido que impedirá a abertura do documento por certos agentes de usuário ou versões anteriores desses agentes. |
| [UnexpectedContent](#UnexpectedContent) | Algum conteúdo no documento de origem não pôde ser reconhecido (ou seja, |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

Foi detectado um problema no documento de origem que torna muito provável que o documento não possa ser aberto se for salvo em seu formato original.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

Texto/gráfico/imagem ou outros dados estarão completamente ausentes tanto da árvore de documentos após o carregamento quanto do documento criado após a gravação.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Grande perda de formatação.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Pequena perda de formatação.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Este é um problema conhecido que impedirá a abertura do documento por certos agentes de usuário ou versões anteriores desses agentes.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Algum conteúdo no documento de origem não pôde ser reconhecido (ou seja, não é suportado), isso pode ou não causar problemas ou resultar em perda de dados ou formatação.