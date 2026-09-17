---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions 枚举

包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。

PdfAccessPermissions 类型公开以下成员：

## 字段

| 字段 | 描述 |
| :- | :- |
| NONE | 指定用户没有访问权限。 |
| PRINT_DOCUMENT | 指定用户是否可以打印文档（可能不是最高质量级别，取决于 <br/>是否位 [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/zh/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) 也被设置）。 |
| MODIFY_CONTENT | 指定用户是否可以通过除位 [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/zh/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS)、[`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/zh/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS)、[`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/zh/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT) 控制的操作之外的方式<br/>修改文档内容。 |
| COPY_TEXT_AND_GRAPHICS | 指定用户是否可以通过除位 [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/zh/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS) 控制的操作之外的方式<br/>复制或提取文档中的文本和图形。 |
| ADD_OR_MODIFY_FIELDS | 指定用户是否可以添加或修改文本批注、填写交互式表单字段；如果位<br/>[`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/zh/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) 也被设置，则可以创建或修改交互式表单字段（包括签名<br/>字段）。 |
| FILL_EXISTING_FIELDS | 指定用户是否可以填写现有的交互式表单字段（包括签名字段），即使位<br/>[`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/zh/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) 未设置。 |
| EXTRACT_TEXT_AND_GRAPHICS | 指定用户是否可以提取文本和图形，以支持残障用户的可访问性<br/>或出于其他目的。 |
| ASSEMBLE_DOCUMENT | 指定用户是否可以组装文档（插入、旋转或删除页面并创建书签或<br/>缩略图），即使位 [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/zh/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) 未设置。 |
| HIGH_QUALITY_PRINT | 指定用户是否可以将文档打印为可生成 PDF 内容忠实数字副本的表示。<br/>当此位未设置（且位 [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/zh/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) 已设置），<br/>打印将限制为外观的低层次表示，可能质量下降。 |

### 另见
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)