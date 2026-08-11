---
title: With()
second_title: مرجع API Aspose.Slides برای C++
description: رکورد مرجع را کلون می‌کند و تابع مقداردهی اولیه را بر آن اعمال می‌نماید.
type: docs
weight: 2614
url: /fa/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) تابع

رکورد مرجع را کلون می‌کند و تابع مقداردهی اولیه را بر آن اعمال می‌نماید.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | Record type to clone. |
| A | Initialization functor type. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | اشاره‌گر مشترک به شیء برای کلون و مقداردهی اولیه. |
| initializer | const A\& | تابع مقداردهی اولیه که بر کلون رکورد اعمال می‌شود. |

### مقدار بازگشتی

اشاره‌گر مشترک به رکورد کلون‌شده.

## System::With(const T\&, const A\&) تابع

رکورد ساختار را کپی می‌کند و تابع مقداردهی اولیه را بر آن اعمال می‌کند.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | Record type to copy. |
| A | Initialization functor type. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| record | const T\& | رکورد برای کپی و مقداردهی اولیه. |
| initializer | const A\& | تابع مقداردهی اولیه که بر نسخه کپی شده رکورد اعمال می‌شود. |

### مقدار بازگشتی

رکورد کپی‌شده.

## موارد مرتبط

* Typedef [SharedPtr](../sharedptr/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)