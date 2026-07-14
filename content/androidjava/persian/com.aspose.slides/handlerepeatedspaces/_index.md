---
title: HandleRepeatedSpaces
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مشخص می‌کند که چگونه کاراکترهای فضای عادی تکراری باید هنگام صادرات مارک‌داون پردازش شوند.
type: docs
url: /fa/com.aspose.slides/handlerepeatedspaces/
---
**ارث‌بری:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

مشخص می‌کند که چگونه کاراکترهای فضای عادی تکراری باید هنگام صادرات مارک‌داون پردازش شوند.
## فیلدها

| فیلد | توضیح |
| --- | --- |
| [None](#None) | تمام فضاها به عنوان کاراکترهای فضای عادی بدون هیچ تغییری حفظ می‌شوند. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | دنباله‌های دو یا بیشتر فضای عادی متوالی را با جابجایی بین کاراکترهای فضای عادی و موجودیت‌های فضای غیرقابل شکست (NBSP) تبدیل می‌کند. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | دنباله‌های دو یا بیشتر فضای عادی متوالی را با حفظ اولین فضای عادی به عنوان کاراکتر فضای عادی و جایگزینی تمام فضاهای بعدی با موجودیت‌های فضای غیرقابل شکست (NBSP) تبدیل می‌کند. |
### None {#None}
```
public static final int None
```

تمام فضاها به عنوان کاراکترهای فضای عادی بدون هیچ تغییری حفظ می‌شوند. هیچ تبدیلی اعمال نمی‌شود و فضاهای متوالی متعدد همان‌گونه صادر می‌شوند.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

دنباله‌های دو یا بیشتر فضای عادی متوالی را با جابجایی بین کاراکترهای فضای عادی و موجودیت‌های فضای غیرقابل شکست (NBSP) تبدیل می‌کند. اولین فضای عادی همیشه به عنوان فضای عادی حفظ می‌شود.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

دنباله‌های دو یا بیشتر فضای عادی متوالی را با حفظ اولین فضای عادی به عنوان کاراکتر فضای عادی و جایگزینی تمام فضاهای بعدی با موجودیت‌های فضای غیرقابل شکست (NBSP) تبدیل می‌کند.