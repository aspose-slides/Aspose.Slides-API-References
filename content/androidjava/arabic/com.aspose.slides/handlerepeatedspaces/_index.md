---
title: HandleRepeatedSpaces
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد كيفية التعامل مع أحرف المسافة العادية المتكررة أثناء تصدير Markdown.
type: docs
url: /ar/com.aspose.slides/handlerepeatedspaces/
---
**الوراثة:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

يحدد كيفية التعامل مع أحرف المسافة العادية المتكررة أثناء تصدير Markdown.

## الحقول

| الحقل | الوصف |
| --- | --- |
| [None](#None) | يتم الحفاظ على جميع المسافات كحروف مسافة عادية دون أي تغيير. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | يحوّل سلاسل من مسافتين أو أكثر متتالية من المسافات العادية بالتناوب بين حروف المسافة العادية وكيانات المسافة غير القابلة للكسر NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | يحوّل سلاسل من مسافتين أو أكثر متتالية من المسافات العادية عبر الحفاظ على المسافة الأولى كحرف مسافة عادي واستبدال جميع المسافات اللاحقة بكيانات المسافة غير القابلة للكسر NBSP. |
### None {#None}
```
public static final int None
```

يتم الحفاظ على جميع المسافات كحروف مسافة عادية دون أي تغيير. لا يتم تطبيق أي تحويل، ويتم تصدير المسافات المتتالية كما هي.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

يحويل سلاسل من مسافتين أو أكثر متتالية من المسافات العادية بالتناوب بين حروف المسافة العادية وكيانات المسافة غير القابلة للكسر NBSP. يتم دائمًا الحفاظ على المسافة الأولى كمسافة عادية.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

يحويل سلاسل من مسافتين أو أكثر متتالية من المسافات العادية عبر الحفاظ على المسافة الأولى كحرف مسافة عادي واستبدال جميع المسافات اللاحقة بكيانات المسافة غير القابلة للكسر NBSP.