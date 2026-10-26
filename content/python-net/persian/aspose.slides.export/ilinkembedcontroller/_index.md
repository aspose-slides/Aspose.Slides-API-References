---
title: ILinkEmbedController class
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController کلاس

رابط callback که برای تعیین نحوه پردازش شیء هنگام ذخیره‌سازی استفاده می‌شود.

نوع ILinkEmbedController اعضای زیر را نمایش می‌دهد:

## متدها

| متد | توضیح |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/fa/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | مشخص می‌کند که شیء باید در کجا ذخیره شود.<br/>            این متد یک بار برای هر شناسه شیء فراخوانی می‌شود.<br/>            تضمینی وجود ندارد که دو شیء با داده، semanticName و contentType یکسان اما شناسه متفاوت وجود نداشته باشند. |
| [`get_url(self, id, referrer)`](/slides/python-net/fa/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | یک URL به شیء خارجی را برمی‌گرداند.<br/>            این متد همیشه فراخوانی می‌شود اگر **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.LINK`](/slides/python-net/fa/aspose.slides.export/linkembeddecision/LINK) را برگرداند و ممکن است فراخوانی شود اگر **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.EMBED`](/slides/python-net/fa/aspose.slides.export/linkembeddecision/EMBED) را برگرداند اما جاسازی ممکن نیست.<br/>            می‌تواند برای همان شناسه شیء چندین بار فراخوانی شود. |
| [`save_external(self, id, entity_data)`](/slides/python-net/fa/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | آبجکت خارجی را ذخیره می‌کند. |

### موارد مرتبط
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)