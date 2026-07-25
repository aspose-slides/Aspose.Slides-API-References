---
title: WarningType
second_title: Aspose.Slides for C++ API リファレンス
description: 警告のタイプを表します。
type: docs
weight: 92
url: /ja/aspose.slides.warnings/warningtype/
---
## WarningType 列挙型

警告のタイプを表します。

```cpp
enum class WarningType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| SourceFileCorruption | 0 | ソース文書で問題が検出されました。この問題により、元の形式で保存された場合、文書を開くことができない可能性が非常に高くなります。 |
| DataLoss | 1 | テキスト、チャート、画像、またはその他のデータが、ロード後のドキュメントツリー、または保存後に作成されたドキュメントから完全に欠落します。 |
| MajorFormattingLoss | 2 | 大幅な書式の損失。 |
| MinorFormattingLoss | 3 | 軽微な書式の損失。 |
| CompatibilityIssue | 4 | これは既知の問題で、特定のユーザーエージェントまたは以前のバージョンのユーザーエージェントでは文書を開くことができなくなります。 |
| UnexpectedContent | 99 | ソース文書内の一部のコンテンツが認識できません（つまり、サポートされていません）。これにより問題が発生したり、データや書式が失われる可能性があります。 |

## 参照

* 名前空間 [Aspose::Slides::Warnings](../)
* ライブラリ [Aspose.Slides](../../)