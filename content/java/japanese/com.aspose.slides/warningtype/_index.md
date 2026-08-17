---
title: WarningType
second_title: Aspose.Slides for Java API リファレンス
description: 警告の種類を表します。
type: docs
url: /ja/com.aspose.slides/warningtype/
---
**継承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

警告の種類を表します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | ソースドキュメントで問題が検出されました。この問題により、元の形式で保存した場合、ドキュメントを開くことができない可能性が非常に高くなります。 |
| [DataLoss](#DataLoss) | テキスト/チャート/画像、またはその他のデータが、ロード後のドキュメントツリーまたは保存後に作成されたドキュメントから完全に欠落します。 |
| [MajorFormattingLoss](#MajorFormattingLoss) | 重大な書式の損失。 |
| [MinorFormattingLoss](#MinorFormattingLoss) | 軽微な書式の損失。 |
| [CompatibilityIssue](#CompatibilityIssue) | これは既知の問題で、特定のユーザーエージェントや以前のバージョンのユーザーエージェントではドキュメントを開くことができません。 |
| [UnexpectedContent](#UnexpectedContent) | ソースドキュメント内の一部のコンテンツが認識できませんでした（例 |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

ソースドキュメントで問題が検出されました。この問題により、元の形式で保存した場合、ドキュメントを開くことができない可能性が非常に高くなります。

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

テキスト/チャート/画像、またはその他のデータが、ロード後のドキュメントツリーまたは保存後に作成されたドキュメントから完全に欠落します。

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

重大な書式の損失。

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

軽微な書式の損失。

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

これは既知の問題で、特定のユーザーエージェントや以前のバージョンのユーザーエージェントではドキュメントを開くことができません。

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

ソースドキュメント内の一部のコンテンツが認識できませんでした（サポートされていない）。これにより問題が発生したり、データや書式の損失が生じる可能性がありますが、必ずしもそうなるわけではありません。