---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions 列挙体

このフラグセットは、文書がユーザーアクセスで開かれたときに付与すべきアクセス許可を指定します。

PdfAccessPermissions 型は以下のメンバーを公開します：

## フィールド

| フィールド | 説明 |
| :- | :- |
| NONE | ユーザーがアクセス権を持っていないことを示します。 |
| PRINT_DOCUMENT | ユーザーが文書を印刷できるかどうかを示します（最高品質レベルでない場合があり、<br/>ビット [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/ja/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) が設定されているかどうかに依存します）。 |
| MODIFY_CONTENT | ユーザーが、<br/>ビット [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/ja/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/ja/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/ja/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT) によって制御される操作以外の操作で文書の内容を変更できるかどうかを示します。 |
| COPY_TEXT_AND_GRAPHICS | ユーザーが、<br/>ビット [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/ja/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS) によって制御される操作以外の操作で、文書からテキストやグラフィックをコピーまたは抽出できるかどうかを示します。 |
| ADD_OR_MODIFY_FIELDS | ユーザーがテキスト注釈を追加または変更し、インタラクティブなフォームフィールドに入力でき、さらに<br/>ビット [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/ja/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) が設定されている場合は、インタラクティブなフォームフィールド（署名フィールドを含む）を作成または変更できるかどうかを示します。 |
| FILL_EXISTING_FIELDS | ビット [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/ja/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) がクリアされていても、<br/>ユーザーが既存のインタラクティブなフォームフィールド（署名フィールドを含む）に入力できるかどうかを示します。 |
| EXTRACT_TEXT_AND_GRAPHICS | ユーザーが障害を持つユーザーへのアクセシビリティ支援や<br/>その他の目的で、テキストとグラフィックを抽出できるかどうかを示します。 |
| ASSEMBLE_DOCUMENT | ビット [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/ja/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) がクリアされていても、<br/>ユーザーが文書を組み立て（ページの挿入、回転、削除、ブックマークやサムネイル画像の作成）できるかどうかを示します。 |
| HIGH_QUALITY_PRINT | ユーザーが PDF コンテンツの忠実なデジタルコピーを生成できる表現へ文書を印刷できるかどうかを示します。<br/>このビットがクリアされ（かつビット [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/ja/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) が設定されている）場合、印刷は外観の低レベル表現に制限され、品質が劣化する可能性があります。 |

### 参照
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)