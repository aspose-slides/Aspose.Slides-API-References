---
title: PdfAccessPermissions
second_title: Aspose.Slides for C++ API リファレンス
description: ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス権限を指定するフラグの集合を含みます。
type: docs
weight: 989
url: /ja/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions 列挙型

Contains a set of flags specifying which access permissions should be granted when the document is opened with user access.

```cpp
enum class PdfAccessPermissions
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | ユーザーがアクセス権を持たないことを指定します。 |
| PrintDocument | 4 | ユーザーが文書を印刷できるかどうかを指定します（[PdfAccessPermissions::HighQualityPrint](./) ビットが設定されているかどうかに応じて、最高品質レベルでない可能性があります）。 |
| ModifyContent | 8 | ユーザーがビット [PdfAccessPermissions::AddOrModifyFields](./)、[PdfAccessPermissions::FillExistingFields](./)、[PdfAccessPermissions::AssembleDocument](./) で制御される操作以外の操作で文書の内容を変更できるかどうかを指定します。 |
| CopyTextAndGraphics | 16 | ユーザーがビット [PdfAccessPermissions::ExtractTextAndGraphics](./) で制御される操作以外の操作で文書からテキストやグラフィックをコピーまたは抽出できるかどうかを指定します。 |
| AddOrModifyFields | 32 | ユーザーがテキスト注釈を追加または変更し、インタラクティブなフォームフィールドに入力できるかどうか、さらにビット [PdfAccessPermissions::ModifyContent](./) が設定されている場合はインタラクティブなフォームフィールド（署名フィールドを含む）を作成または変更できるかどうかを指定します。 |
| FillExistingFields | 256 | ビット [PdfAccessPermissions::AddOrModifyFields](./) がクリアされている場合でも、ユーザーが既存のインタラクティブなフォームフィールド（署名フィールドを含む）に入力できるかどうかを指定します。 |
| ExtractTextAndGraphics | 512 | 障害のあるユーザーへのアクセシビリティ支援やその他の目的のために、ユーザーがテキストとグラフィックを抽出できるかどうかを指定します。 |
| AssembleDocument | 1024 | ビット [PdfAccessPermissions::ModifyContent](./) がクリアされている場合でも、ユーザーが文書を組み立て（ページの挿入、回転、削除、ブックマークやサムネイル画像の作成）できるかどうかを指定します。 |
| HighQualityPrint | 2048 | ユーザーが PDF 内容の正確なデジタルコピーを生成できる表現に文書を印刷できるかどうかを指定します。このビットがクリアされ（かつビット [PdfAccessPermissions::PrintDocument](./) が設定されている）場合、印刷は外観の低レベル表現に制限され、品質が低下する可能性があります。 |

## 参照

* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)