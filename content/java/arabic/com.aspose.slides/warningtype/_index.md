---
title: WarningType
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل نوعًا من التحذير.
type: docs
url: /ar/com.aspose.slides/warningtype/
---
**الإرث:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

يمثل نوعًا من التحذير.

## الحقول

| الخاصية | الوصف |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | تم اكتشاف مشكلة في المستند المصدر تجعل من المحتمل جدًا أن لا يكون المستند قادرًا على الفتح إذا تم حفظه بصيغته الأصلية. |
| [DataLoss](#DataLoss) | سيصبح النص/الرسم البياني/الصورة أو أي بيانات أخرى مفقودة بالكامل إما من شجرة المستند بعد التحميل، أو من المستند المُنشأ بعد الحفظ. |
| [MajorFormattingLoss](#MajorFormattingLoss) | فقدان تنسيق كبير. |
| [MinorFormattingLoss](#MinorFormattingLoss) | فقدان تنسيق طفيف. |
| [CompatibilityIssue](#CompatibilityIssue) | هذه مشكلة معروفة ستمنع فتح المستند بواسطة بعض عوامل المستخدم، أو إصدارات سابقة من عوامل المستخدم. |
| [UnexpectedContent](#UnexpectedContent) | لم يتمكن من التعرف على بعض المحتوى في المستند المصدر (i.e. |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

تم اكتشاف مشكلة في المستند المصدر تجعل من المحتمل جدًا أن لا يكون المستند قادرًا على الفتح إذا تم حفظه بصيغته الأصلية.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

سيصبح النص/الرسم البياني/الصورة أو أي بيانات أخرى مفقودة بالكامل إما من شجرة المستند بعد التحميل، أو من المستند المُنشأ بعد الحفظ.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

فقدان تنسيق كبير.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

فقدان تنسيق طفيف.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

هذه مشكلة معروفة ستمنع فتح المستند بواسطة بعض عوامل المستخدم، أو إصدارات سابقة من عوامل المستخدم.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

لم يتمكن من التعرف على بعض المحتوى في المستند المصدر (i.e. is unsupported), this may or may not cause issues or result in data/formatting loss.