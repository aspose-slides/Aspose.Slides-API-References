---
title: PPImage class
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ppimage/
---
## PPImage کلاس

یک تصویر در ارائه را نشان می‌دهد.

نوع PPImage اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`binary_data`](/slides/python-net/fa/aspose.slides/ppimage/binary_data/) | کپی داده‌های تصویر را برمی‌گرداند.<br/>            فقط‌خواندنی **int**[]. |
| [`image`](/slides/python-net/fa/aspose.slides/ppimage/image/) | کپی تصویر را برمی‌گرداند.<br/>            فقط‌خواندنی [`IImage`](/slides/python-net/fa/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/fa/aspose.slides/ppimage/svg_image/) | [`ISvgImage`](/slides/python-net/fa/aspose.slides/isvgimage) شیء ISvgImage را برمی‌گرداند یا تنظیم می‌کند |
| [`content_type`](/slides/python-net/fa/aspose.slides/ppimage/content_type/) | نوع MIME یک تصویر را که در [`PPImage.binary_data`](/slides/python-net/fa/aspose.slides/ppimage/binary_data) رمزگذاری شده است برمی‌گرداند.<br/>            فقط‌خواندنی **str**. |
| [`width`](/slides/python-net/fa/aspose.slides/ppimage/width/) | عرض یک تصویر را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`height`](/slides/python-net/fa/aspose.slides/ppimage/height/) | ارتفاع یک تصویر را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`x`](/slides/python-net/fa/aspose.slides/ppimage/x/) | مقدار X-offset یک تصویر را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`y`](/slides/python-net/fa/aspose.slides/ppimage/y/) | مقدار Y-offset یک تصویر را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |

## متدها

| متد | توضیح |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/fa/aspose.slides/ppimage/replace_image/#bytes) | داده‌های تصویر را جایگزین می‌کند.<br/>            داده‌های تصویر جدید. وقتی پارامتر newImageData مقدار None باشد. |
| [`replace_image(self, new_image)`](/slides/python-net/fa/aspose.slides/ppimage/replace_image/#iimage) | داده‌های تصویر را جایگزین می‌کند. توجه: وقتی Image یک متافایل است - تبدیل به رستر می‌شود. به جای آن از ReplaceImage(byte[]) استفاده کنید<br/>            تصویر جدید. وقتی پارامتر newImage مقدار None باشد. |
| [`replace_image(self, new_image)`](/slides/python-net/fa/aspose.slides/ppimage/replace_image/#ippimage) | داده‌های تصویر را جایگزین می‌کند.<br/>            IPPImage جدید. وقتی پارامتر newImage مقدار None باشد. |

### مراجع
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)