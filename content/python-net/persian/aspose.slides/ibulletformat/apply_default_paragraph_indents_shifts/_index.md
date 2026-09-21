---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
در صورتی که bullets فعال باشد، جابجاهای پیش‌فرض غیر صفر برای Indent و MarginLeft مؤثر پاراگراف تنظیم می‌شود (مانند PowerPoint هنگامی که bullets/شماره‌گذاری پاراگراف را فعال می‌کند). اگر bullets غیرفعال باشد، فقط Indent و MarginLeft پاراگراف بازنشانی می‌شوند (مانند PowerPoint هنگامی که bullets/شماره‌گذاری پاراگراف را غیرفعال می‌کند). جابجاهای Indents بر اساس زمینه فعلی bullet اعمال می‌شوند - IBulletFormat.Type، .NumberedBulletStyle و FontHeight اولین بخش. جابجاهای غیر صفر indents به Indent و MarginLeft مؤثر پاراگراف جاری اعمال می‌شوند (تا مقادیر نتیجه به مقادیر محلی تبدیل شوند).

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### استثنائات

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | در موارد زیر، فراخوانی این متد بی‌توجه است و **System.InvalidOperationException** را پرتاب می‌کند:<br/>            اگر شیء فرمت والد یک پاراگراف نباشد (به عنوان مثال فراخوانی ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() یک استثنا پرتاب می‌کند)؛<br/>            یا اگر پاراگراف به هیچ مجموعه ITextFrame.Paragraphs اضافه نشده باشد (ابتدا آن را اضافه کنید)؛ |

### موارد مرتبط
* کلاس [`IBulletFormat`](/slides/python-net/fa/aspose.slides/ibulletformat)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)