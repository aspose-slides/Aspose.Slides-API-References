---
title: CombineMode
second_title: Aspose.Slides برای C++ API Reference
description: نحوه ترکیب نواحی برش را مشخص می‌کند.
type: docs
weight: 170
url: /fa/system.drawing.drawing2d/combinemode/
---
## CombineMode enum

Specifies how clipping regions are combined.

```cpp
enum class CombineMode
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| Replace | 0 | یک ناحیهٔ برش توسط ناحیهٔ دیگری جایگزین می‌شود. |
| Intersect | 1 | دو ناحیهٔ برش با گرفتن اشتراکشان ترکیب می‌شوند. |
| Union | 2 | دو ناحیهٔ برش با گرفتن اتحاد هر دو ترکیب می‌شوند. |
| Xor | 3 | دو ناحیهٔ برش با گرفتن تنها ناحیه‌ای که توسط یکی از نواحی محصور شده است، اما نه هر دو، ترکیب می‌شوند. |
| Exclude | 4 | دو ناحیهٔ برش با گرفتن ناحیهٔ اول که با دوم تقاطع ندارد ترکیب می‌شوند. |
| Complement | 5 | دو ناحیهٔ برش با گرفتن ناحیهٔ دوم که با اولین تقاطع ندارد ترکیب می‌شوند. |

## موارد مرتبط

* فضای‌نام [System::Drawing::Drawing2D](../)
* کتابخانه [Aspose.Slides](../../)