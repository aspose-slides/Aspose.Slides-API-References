---
title: PdfAccessPermissions
second_title: Aspose.Slides for Android via Java API 参考
description: 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。
type: docs
url: /zh/com.aspose.slides/pdfaccesspermissions/
---
**继承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。
## 字段

| 字段 | 描述 |
| --- | --- |
| [None](#None) | 指定用户不具有访问权限。 |
| [PrintDocument](#PrintDocument) | 指定用户是否可以打印文档（可能不是最高质量级别，取决于位 [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) 是否也被设置）。 |
| [ModifyContent](#ModifyContent) | 指定用户是否可以通过除位 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)、[FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields)、[AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) 控制的操作之外的操作来修改文档内容。 |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | 指定用户是否可以通过除位 [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) 控制的操作之外的操作来复制或以其他方式提取文档中的文本和图形。 |
| [AddOrModifyFields](#AddOrModifyFields) | 指定用户是否可以添加或修改文本批注、填写交互式表单字段，并且如果位 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) 也被设置，则可以创建或修改交互式表单字段（包括签名字段）。 |
| [FillExistingFields](#FillExistingFields) | 指定用户是否可以填写现有的交互式表单字段（包括签名字段），即使位 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) 未被设置。 |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | 指定用户是否可以提取文本和图形，以支持残障用户的可访问性或用于其他目的。 |
| [AssembleDocument](#AssembleDocument) | 指定用户是否可以组装文档（插入、旋转或删除页面并创建书签或缩略图），即使位 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) 未被设置。 |
| [HighQualityPrint](#HighQualityPrint) | 指定用户是否可以将文档打印为一种表示形式，从中可以生成 PDF 内容的忠实数字副本。 |

### 无 {#None}
```
public static final int None
```

指定用户不具有访问权限。

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

指定用户是否可以打印文档（可能不是最高质量级别，取决于位 [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) 是否也被设置）。

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

指定用户是否可以通过除位 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)、[FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields)、[AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) 控制的操作之外的操作来修改文档内容。

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

指定用户是否可以通过除位 [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) 控制的操作之外的操作来复制或以其他方式提取文档中的文本和图形。

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

指定用户是否可以添加或修改文本批注、填写交互式表单字段，并且如果位 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) 也被设置，则可以创建或修改交互式表单字段（包括签名字段）。

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

指定用户是否可以填写现有的交互式表单字段（包括签名字段），即使位 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) 未被设置。

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

指定用户是否可以提取文本和图形，以支持残障用户的可访问性或用于其他目的。

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

指定用户是否可以组装文档（插入、旋转或删除页面并创建书签或缩略图），即使位 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) 未被设置。

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

指定用户是否可以将文档打印为一种表示形式，从中可以生成 PDF 内容的忠实数字副本。当此位为未设置状态（且位 [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) 已被设置），打印将限制为外观的低级表示，可能导致质量下降。