---
title: HandleRepeatedSpaces
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يحدد كيفية التعامل مع الأحرف المتكررة للمسافات العادية أثناء تصدير Markdown.
type: docs
url: /ar/com.aspose.slides/handlerepeatedspaces/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

يحدد كيفية التعامل مع الأحرف المتكررة للمسافات العادية أثناء تصدير Markdown.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [None](#None) | جميع المسافات تُحافظ عليها كأحرف مسافة عادية دون أي تغييرات. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | يحول تسلسلات مساحة عادية متتابعة (اثنتين أو أكثر) عن طريق التناوب بين أحرف المسافة العادية وكيانات المسافة غير القابلة للكسر NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | يحول تسلسلات مساحة عادية متتابعة (اثنتين أو أكثر) عن طريق الحفاظ على المسافة الأولى كمسافة عادية واستبدال جميع المسافات اللاحقة بكيانات المسافة غير القابلة للكسر NBSP. |
### None {#None}
```
public static final int None
```

جميع المسافات تُحافظ عليها كأحرف مسافة عادية دون أي تغييرات. لا يتم تطبيق أي تحويل، وتُصدر المسافات المتتالية المتعددة كما هي.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

يحول تسلسلات مساحة عادية متتابعة (اثنتين أو أكثر) عن طريق التناوب بين أحرف المسافة العادية وكيانات المسافة غير القابلة للكسر NBSP. دائمًا ما تُحافظ على المسافة الأولى كمسافة عادية.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

يحول تسلسلات مساحة عادية متتابعة (اثنتين أو أكثر) عن طريق الحفاظ على المسافة الأولى كمسافة عادية واستبدال جميع المسافات اللاحقة بكيانات المسافة غير القابلة للكسر NBSP.