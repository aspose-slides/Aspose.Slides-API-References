---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides برای Python از طریق .NET API مرجع
description: 
type: docs
url: /fa/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
مقادیر پیش‌فرض جابه‌جایی‌های غیر صفر برای Indent و MarginLeft مؤثر پاراگراف تنظیم می‌کند وقتی که بولت‌ها فعال باشد (مانند کاری که PowerPoint هنگام فعال‌سازی بولت‌ها/شماره‌گذاری پاراگراف انجام می‌دهد). اگر بولت‌ها غیرفعال باشد فقط Indent و MarginLeft پاراگراف بازنشانی می‌شود (مانند کاری که PowerPoint هنگام غیرفعال‌سازی بولت‌ها/شماره‌گذاری پاراگراف انجام می‌دهد). جابه‌جایی‌های تو رفتگی نسبت به زمینه فعلی بولت – IBulletFormat.Type، .NumberedBulletStyle و FontHeight اولین بخش – اعمال می‌شود. جابه‌جایی‌های غیر صفر تو رفتگی به Indent و MarginLeft مؤثر پاراگراف فعلی اعمال می‌شوند (تا مقادیر نتیجه به‌عنوان مقادیر محلی درآیند).

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | فراخوانی این متد هیچ اهمیتی ندارد و در موارد زیر **System.InvalidOperationException** پرتاب می‌شود:<br/>            اگر شیء قالب‌بندی والد یک پاراگراف نباشد (به عنوان مثال فراخوانی ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() باعث پرتاب استثنا می‌شود)؛<br/>            یا اگر پاراگراف به هیچ مجموعه ITextFrame.Paragraphs اضافه نشده باشد (ابتدا آن را اضافه کنید)؛ |

### موارد مرتبط
* کلاس [`BulletFormat`](/slides/python-net/fa/aspose.slides/bulletformat)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)