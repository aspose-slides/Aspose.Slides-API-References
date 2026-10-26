---
title: interruption_token property
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token ویژگی
توکنی که برای نظارت بر درخواست‌های قطع استفاده می‌شود.

این توکن کل طول عمر نمونه [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری یا ذخیره‌سازی ارائه، از طریق فراخوانی متد [`IInterruptionTokenSource.interrupt`](/slides/python-net/fa/aspose.slides/iinterruptiontokensource/interrupt) از [`IInterruptionTokenSource`](/slides/python-net/fa/aspose.slides/iinterruptiontokensource) متوقف خواهد شد.

### تعریف:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### موارد مرتبط
* کلاس [`IInterruptionTokenSource`](/slides/python-net/fa/aspose.slides/iinterruptiontokensource)
* کلاس [`ILoadOptions`](/slides/python-net/fa/aspose.slides/iloadoptions)
* کلاس [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)