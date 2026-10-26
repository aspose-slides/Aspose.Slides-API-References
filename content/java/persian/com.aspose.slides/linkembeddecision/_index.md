---
title: LinkEmbedDecision
second_title: مرجع API Aspose.Slides برای جاوا
description: تعیین می‌کند که شی در هنگام ذخیره‌سازی چگونه پردازش شود.
type: docs
url: /fa/com.aspose.slides/linkembeddecision/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

تعیین می‌کند که شی در هنگام ذخیره‌سازی چگونه پردازش شود.
## Fields

| Field | Description |
| --- | --- |
| [Link](#Link) | شی به صورت خارجی ذخیره می‌شود و از طریق URL ارجاع داده می‌شود |
| [Embed](#Embed) | در صورت امکان، شی باید در فایلی تولید شده جاسازی شود. |
| [Ignore](#Ignore) | شی نادیده گرفته می‌شود. |
### پیوند {#Link}
```
public static final int Link
```


شی به صورت خارجی ذخیره می‌شود و از طریق URL ارجاع داده می‌شود

### جاسازی {#Embed}
```
public static final int Embed
```


در صورت امکان، شی باید در فایلی تولید شده جاسازی شود. اگر جاسازی ممکن نباشد، GetUrl فراخوانی می‌شود و بسته به نتیجه، شی یا از طریق URL ارجاع داده می‌شود یا نادیده گرفته می‌شود.

### نادیده‌گیری {#Ignore}
```
public static final int Ignore
```


شی نادیده گرفته می شود.