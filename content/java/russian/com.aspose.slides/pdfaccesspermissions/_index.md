---
title: PdfAccessPermissions
second_title: Aspose.Slides для Java – справочник API
description: Содержит набор флагов, указывающих, какие разрешения доступа следует предоставить при открытии документа пользователем.
type: docs
url: /ru/com.aspose.slides/pdfaccesspermissions/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем.
## Поля

| Поле | Описание |
| --- | --- |
| [None](#None) | Указывает, что пользователь не имеет прав доступа. |
| [PrintDocument](#PrintDocument) | Указывает, может ли пользователь печатать документ (возможно, не в самом высоком качестве, в зависимости от того, установлен ли также бит [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint)). |
| [ModifyContent](#ModifyContent) | Указывает, может ли пользователь изменять содержимое документа операциями, отличными от контролируемых битами [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Указывает, может ли пользователь копировать или иначе извлекать текст и графику из документа операциями, отличными от контролируемых битом [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Указывает, может ли пользователь добавлять или изменять текстовые аннотации, заполнять интерактивные поля формы, и, если установлен бит [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent), создавать или изменять интерактивные поля формы (включая поля подписи). |
| [FillExistingFields](#FillExistingFields) | Указывает, может ли пользователь заполнять существующие интерактивные поля формы (включая поля подписи), даже если бит [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) снят. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Указывает, может ли пользователь извлекать текст и графику в целях обеспечения доступности для пользователей с ограниченными возможностями или для иных целей. |
| [AssembleDocument](#AssembleDocument) | Указывает, может ли пользователь объединять документ (вставлять, вращать или удалять страницы и создавать закладки или миниатюры), даже если бит [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) снят. |
| [HighQualityPrint](#HighQualityPrint) | Указывает, может ли пользователь печатать документ в представление, из которого может быть создана точная цифровая копия содержимого PDF. |
### None {#None}
```
public static final int None
```

Указывает, что пользователь не имеет прав доступа.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Указывает, может ли пользователь печатать документ (возможно, не в самом высоком качестве, в зависимости от того, установлен ли также бит [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint)).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Указывает, может ли пользователь изменять содержимое документа операциями, отличными от контролируемых битами [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Указывает, может ли пользователь копировать или иначе извлекать текст и графику из документа операциями, отличными от контролируемых битом [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Указывает, может ли пользователь добавлять или изменять текстовые аннотации, заполнять интерактивные поля формы, и, если установлен бит [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent), создавать или изменять интерактивные поля формы (включая поля подписи).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Указывает, может ли пользователь заполнять существующие интерактивные поля формы (включая поля подписи), даже если бит [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) снят.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Указывает, может ли пользователь извлекать текст и графику в целях обеспечения доступности для пользователей с ограниченными возможностями или для иных целей.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Указывает, может ли пользователь объединять документ (вставлять, вращать или удалять страницы и создавать закладки или миниатюры), даже если бит [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) снят.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Указывает, может ли пользователь печатать документ в представление, из которого может быть создана точная цифровая копия содержимого PDF. Когда этот бит снят (и бит [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) установлен), печать ограничивается низкоуровневым представлением внешнего вида, возможно, с ухудшенным качеством.