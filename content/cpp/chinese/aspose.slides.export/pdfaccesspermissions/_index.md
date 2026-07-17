---
title: PdfAccessPermissions
second_title: Aspose.Slides C++ API 参考
description: 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。
type: docs
weight: 989
url: /zh/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions 枚举

包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。

```cpp
enum class PdfAccessPermissions
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 指定用户没有访问权限。 |
| PrintDocument | 4 | 指定用户是否可以打印文档（可能不是最高质量级别，这取决于位 [PdfAccessPermissions::HighQualityPrint](./) 是否也被设置）。 |
| ModifyContent | 8 | 指定用户是否可以通过除位 [PdfAccessPermissions::AddOrModifyFields](./)、[PdfAccessPermissions::FillExistingFields](./)、[PdfAccessPermissions::AssembleDocument](./) 控制之外的操作修改文档内容。 |
| CopyTextAndGraphics | 16 | 指定用户是否可以通过除位 [PdfAccessPermissions::ExtractTextAndGraphics](./) 控制之外的操作复制或以其他方式提取文档中的文本和图形。 |
| AddOrModifyFields | 32 | 指定用户是否可以添加或修改文本批注、填写交互式表单字段，并且如果位 [PdfAccessPermissions::ModifyContent](./) 也被设置，则可以创建或修改交互式表单字段（包括签名字段）。 |
| FillExistingFields | 256 | 指定用户是否可以填写现有的交互式表单字段（包括签名字段），即使位 [PdfAccessPermissions::AddOrModifyFields](./) 未被设置。 |
| ExtractTextAndGraphics | 512 | 指定用户是否可以提取文本和图形，以支持残障用户的可访问性或出于其他目的。 |
| AssembleDocument | 1024 | 指定用户是否可以组装文档（插入、旋转或删除页面以及创建书签或缩略图），即使位 [PdfAccessPermissions::ModifyContent](./) 未被设置。 |
| HighQualityPrint | 2048 | 指定用户是否可以将文档打印为一种可以生成 PDF 内容的真实数字副本的表示形式。当此位未被设置（且位 [PdfAccessPermissions::PrintDocument](./) 已被设置）时，打印将限制为外观的低级表示，可能质量下降。 |

## 另见

* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)