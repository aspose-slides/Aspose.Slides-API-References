---
title: PdfAccessPermissions
second_title: Aspose.Slides の Java API リファレンス
description: ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス権限を指定するフラグの集合を含みます。
type: docs
url: /ja/com.aspose.slides/pdfaccesspermissions/
---
**継承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス権限を指定するフラグの集合を含みます。

## Fields

| フィールド | 説明 |
| --- | --- |
| [None](#None) | ユーザーにアクセス権が付与されていないことを指定します。 |
| [PrintDocument](#PrintDocument) | ユーザーがドキュメントを印刷できるかどうかを指定します（[HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) ビットが設定されているかどうかに応じて、最高品質でない可能性があります）。 |
| [ModifyContent](#ModifyContent) | ユーザーがビット [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)、[FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields)、[AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) で制御される操作以外の操作でドキュメントの内容を変更できるかどうかを指定します。 |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | ユーザーがビット [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) で制御される操作以外の操作でテキストやグラフィックをコピーまたは抽出できるかどうかを指定します。 |
| [AddOrModifyFields](#AddOrModifyFields) | ユーザーがテキスト注釈を追加または変更し、インタラクティブなフォームフィールドに入力し、さらにビット [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) が設定されている場合、インタラクティブなフォームフィールド（署名フィールドを含む）を作成または変更できるかどうかを指定します。 |
| [FillExistingFields](#FillExistingFields) | ビット [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) がクリアされていても、ユーザーが既存のインタラクティブなフォームフィールド（署名フィールドを含む）に入力できるかどうかを指定します。 |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | ユーザーが障害を持つユーザーへのアクセシビリティ支援やその他の目的でテキストとグラフィックを抽出できるかどうかを指定します。 |
| [AssembleDocument](#AssembleDocument) | ビット [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) がクリアされていても、ユーザーがドキュメントを組み立て（ページの挿入、回転、削除、ブックマークやサムネイル画像の作成）できるかどうかを指定します。 |
| [HighQualityPrint](#HighQualityPrint) | ユーザーがPDFコンテンツの正確なデジタルコピーを生成できる表現にドキュメントを印刷できるかどうかを指定します。 |

### None {#None}
```
public static final int None
```

ユーザーにアクセス権が付与されていないことを指定します。

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

ユーザーがドキュメントを印刷できるかどうかを指定します（[HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) ビットが設定されているかどうかに応じて、最高品質でない可能性があります）。

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

ユーザーがビット [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)、[FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields)、[AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) で制御される操作以外の操作でドキュメントの内容を変更できるかどうかを指定します。

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

ユーザーがビット [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) で制御される操作以外の操作でテキストやグラフィックをコピーまたは抽出できるかどうかを指定します。

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

ユーザーがテキスト注釈を追加または変更し、インタラクティブなフォームフィールドに入力し、さらにビット [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) が設定されている場合、インタラクティブなフォームフィールド（署名フィールドを含む）を作成または変更できるかどうかを指定します。

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

ビット [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) がクリアされていても、ユーザーが既存のインタラクティブなフォームフィールド（署名フィールドを含む）に入力できるかどうかを指定します。

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

ユーザーが障害を持つユーザーへのアクセシビリティ支援やその他の目的でテキストとグラフィックを抽出できるかどうかを指定します。

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

ビット [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) がクリアされていても、ユーザーがドキュメントを組み立て（ページの挿入、回転、削除、ブックマークやサムネイル画像の作成）できるかどうかを指定します。

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

ユーザーがPDFコンテンツの正確なデジタルコピーを生成できる表現にドキュメントを印刷できるかどうかを指定します。このビットがクリアされ（かつ [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) ビットが設定されている）場合、印刷は外観の低レベル表現に制限され、品質が低下する可能性があります。