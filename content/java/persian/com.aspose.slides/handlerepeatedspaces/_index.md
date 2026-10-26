---
title: HandleRepeatedSpaces
second_title: Aspose.Slides برای مرجع API جاوا
description: مشخص می‌کند که چگونه کاراکترهای فضای خالی معمولی تکراری هنگام خروجی‌گیری Markdown باید مدیریت شوند.
type: docs
url: /fa/com.aspose.slides/handlerepeatedspaces/
---
**ارث‌برداری:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

مشخص می‌کند که چگونه کاراکترهای فضای خالی معمولی تکراری هنگام خروجی‌گیری Markdown باید مدیریت شوند.
## فیلدها

| فیلد | توضیح |
| --- | --- |
| [None](#None) | تمام فضاها به عنوان کاراکترهای فضای خالی معمولی بدون هیچ تغییری حفظ می‌شوند. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | دنباله‌های دو یا بیش از دو فضای خالی متوالی را با چرخش بین کاراکترهای فضای خالی معمولی و موجودیت‌های فضای غیرقابل شکست NBSP تبدیل می‌کند. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | دنباله‌های دو یا بیش از دو فضای خالی متوالی را با حفظ اولین فضا به عنوان کاراکتر فضای خالی معمولی و جایگزینی تمام فضاهای بعدی با موجودیت‌های فضای غیرقابل شکست NBSP تبدیل می‌کند. |
### None {#None}
```
public static final int None
```

تمام فضاها به عنوان کاراکترهای فضای خالی معمولی بدون هیچ تغییری حفظ می‌شوند. هیچ تبدیلی اعمال نمی‌شود و فضاهای متوالی چندگانه همان‌گونه صادر می‌شوند.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

دنباله‌های دو یا بیش از دو فضای خالی متوالی را با چرخش بین کاراکترهای فضای خالی معمولی و موجودیت‌های فضای غیرقابل شکست NBSP تبدیل می‌کند. اولین فضا همیشه به عنوان فضای خالی معمولی حفظ می‌شود.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

دنباله‌های دو یا بیش از دو فضای خالی متوالی را با حفظ اولین فضا به عنوان کاراکتر فضای خالی معمولی و جایگزینی تمام فضاهای بعدی با موجودیت‌های فضای غیرقابل شکست NBSP تبدیل می‌کند.