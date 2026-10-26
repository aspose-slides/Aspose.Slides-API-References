---
title: PdfAccessPermissions
second_title: Справочник API Aspose.Slides для Android через Java
description: Содержит набор флагов, указывающих, какие разрешения доступа следует предоставить при открытии документа пользователем.
type: docs
url: /ru/com.aspose.slides/pdfaccesspermissions/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Содержит набор флагов, указывающих, какие разрешения доступа следует предоставить при открытии документа пользователем.
## Поля

| Поле | Описание |
| --- | --- |
| [None](#None) | Указывает, что пользователь не имеет разрешений доступа. |
| [PrintDocument](#PrintDocument) | Указывает, может ли пользователь печатать документ (возможно не в наивысшем качестве, в зависимости от того, установлен ли бит [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint)). |
| [ModifyContent](#ModifyContent) | Указывает, может ли пользователь изменять содержимое документа операциями, отличными от тех, которые контролируются битами [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Указывает, может ли пользователь копировать или иным образом извлекать текст и графику из документа операциями, отличными от контролируемой битом [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Указывает, может ли пользователь добавлять или изменять текстовые аннотации, заполнять интерактивные поля форм и, если установлен бит [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent), создавать или изменять интерактивные поля форм (включая поля подписи). |
| [FillExistingFields](#FillExistingFields) | Указывает, может ли пользователь заполнять существующие интерактивные поля форм (включая поля подписи), даже если бит [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) сброшен. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Указывает, может ли пользователь извлекать текст и графику в поддержу доступности для пользователей с ограниченными возможностями или в других целях. |
| [AssembleDocument](#AssembleDocument) | Указывает, может ли пользователь собирать документ (вставлять, вращать или удалять страницы и создавать закладки или миниатюры), даже если бит [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) сброшен. |
| [HighQualityPrint](#HighQualityPrint) | Указывает, может ли пользователь печатать документ в представление, из которого может быть создана точная цифровая копия содержимого PDF. |
### None {#None}
```
public static final int None
```

Указывает, что пользователь не имеет разрешений доступа.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Указывает, может ли пользователь печатать документ (возможно не в наивысшем качестве, в зависимости от того, установлен ли бит [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint)).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Указывает, может ли пользователь изменять содержимое документа операциями, отличными от контролируемых битами [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Указывает, может ли пользователь копировать или иным образом извлекать текст и графику из документа операциями, отличными от контролируемой битом [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Указывает, может ли пользователь добавлять или изменять текстовые аннотации, заполнять интерактивные поля форм и, если установлен бит [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent), создавать или изменять интерактивные поля форм (включая поля подписи).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Указывает, может ли пользователь заполнять существующие интерактивные поля форм (включая поля подписи), даже если бит [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) сброшен.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Указывает, может ли пользователь извлекать текст и графику в поддержу доступности для пользователей с ограниченными возможностями или в других целях.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Указывает, может ли пользователь собирать документ (вставлять, вращать или удалять страницы и создавать закладки или миниатюры), даже если бит [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) сброшен.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Указывает, может ли пользователь печатать документ в представление, из которого может быть создана точная цифровая копия содержимого PDF. Когда этот бит сброшен (и установлен бит [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument)), печать ограничивается представлением низкого уровня внешнего вида, возможно с ухудшенным качеством.