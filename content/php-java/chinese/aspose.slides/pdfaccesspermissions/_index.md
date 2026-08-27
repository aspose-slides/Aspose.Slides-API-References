---
title: PdfAccessPermissions
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/pdfaccesspermissions/
---
## PdfAccessPermissions 类

包含一组标志，指定在打开文档时应授予哪些访问权限。

## 常量

| 名称 | 值 | 描述 |
| --- | --- | --- |
[None](#None) | 0 | 指定用户没有访问权限。 |
[PrintDocument](#PrintDocument) | 4 | 指定用户是否可以打印文档（可能不是最高质量，取决于位 PdfAccessPermissions#HighQualityPrint 是否也被设置）。 |
[ModifyContent](#ModifyContent) | 8 | 指定用户是否可以通过非由位 PdfAccessPermissions#AddOrModifyFields、PdfAccessPermissions#FillExistingFields、PdfAccessPermissions#AssembleDocument 控制的操作来修改文档内容。 |
[CopyTextAndGraphics](#CopyTextAndGraphics) | 16 | 指定用户是否可以通过非位 PdfAccessPermissions#ExtractTextAndGraphics 控制的操作复制或提取文档中的文本和图形。 |
[AddOrModifyFields](#AddOrModifyFields) | 32 | 指定用户是否可以添加或修改文本注释、填写交互式表单字段，并且如果位 PdfAccessPermissions#ModifyContent 也被设置，则可以创建或修改交互式表单字段（包括签名字段）。 |
[FillExistingFields](#FillExistingFields) | 256 | 指定用户是否可以填写已有的交互式表单字段（包括签名字段），即使位 PdfAccessPermissions#AddOrModifyFields 未被设置。 |
[ExtractTextAndGraphics](#ExtractTextAndGraphics) | 512 | 指定用户是否可以提取文本和图形，以支持残障用户的可访问性或其他目的。 |
[AssembleDocument](#AssembleDocument) | 1024 | 指定用户是否可以组装文档（插入、旋转或删除页面以及创建书签或缩略图），即使位 PdfAccessPermissions#ModifyContent 未被设置。 |
[HighQualityPrint](#HighQualityPrint) | 2048 | 指定用户是否可以将文档打印成可以生成 PDF 内容忠实数字副本的表示。当此位未被设置（且位 PdfAccessPermissions#PrintDocument 已被设置）时，打印仅限于外观的低层次表示，可能质量下降。 |

---

### None {#None}
指定用户没有访问权限。

---

### PrintDocument {#PrintDocument}
指定用户是否可以打印文档（可能不是最高质量，取决于位 PdfAccessPermissions#HighQualityPrint 是否也被设置）。

---

### ModifyContent {#ModifyContent}
指定用户是否可以通过非由位 PdfAccessPermissions#AddOrModifyFields、PdfAccessPermissions#FillExistingFields、PdfAccessPermissions#AssembleDocument 控制的操作来修改文档内容。

---

### CopyTextAndGraphics {#CopyTextAndGraphics}
指定用户是否可以通过非位 PdfAccessPermissions#ExtractTextAndGraphics 控制的操作复制或提取文档中的文本和图形。

---

### AddOrModifyFields {#AddOrModifyFields}
指定用户是否可以添加或修改文本注释、填写交互式表单字段，并且如果位 PdfAccessPermissions#ModifyContent 也被设置，则可以创建或修改交互式表单字段（包括签名字段）。

---

### FillExistingFields {#FillExistingFields}
指定用户是否可以填写已有的交互式表单字段（包括签名字段），即使位 PdfAccessPermissions#AddOrModifyFields 未被设置。

---

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
指定用户是否可以提取文本和图形，以支持残障用户的可访问性或其他目的。

---

### AssembleDocument {#AssembleDocument}
指定用户是否可以组装文档（插入、旋转或删除页面以及创建书签或缩略图），即使位 PdfAccessPermissions#ModifyContent 未被设置。

---

### HighQualityPrint {#HighQualityPrint}
指定用户是否可以将文档打印成可以生成 PDF 内容忠实数字副本的表示。当此位未被设置（且位 PdfAccessPermissions#PrintDocument 已被设置）时，打印仅限于外观的低层次表示，可能质量下降。

---