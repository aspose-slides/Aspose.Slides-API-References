---
title: LinkEmbedDecision
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: مشخص می‌کند که شی هنگام ذخیره‌سازی چگونه پردازش شود.
type: docs
url: /fa/com.aspose.slides/linkembeddecision/
---
**ارث‌برداری:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

مشخص می‌کند که شی هنگام ذخیره‌سازی چگونه پردازش شود.

## فیلدها

| فیلد | توضیح |
| --- | --- |
| [Link](#Link) | شی به‌صورت خارجی ذخیره می‌شود و با URL ارجاع داده می‌شود |
| [Embed](#Embed) | در صورت امکان، شی باید در فایلی که تولید می‌شود درج شود |
| [Ignore](#Ignore) | شی نادیده گرفته خواهد شد |
### لینک {#Link}
```
public static final int Link
```

شی به‌صورت خارجی ذخیره می‌شود و با URL ارجاع داده می‌شود

### جاسازی {#Embed}
```
public static final int Embed
```

در صورت امکان، شی باید در فایلی که تولید می‌شود درج شود. اگر جاسازی امکان‌پذیر نباشد، GetUrl فراخوانی می‌شود و بسته به نتیجه، شی یا با URL ارجاع داده می‌شود یا نادیده گرفته می‌شود.

### نادیده‌گیری {#Ignore}
```
public static final int Ignore
```

شی نادیده گرفته خواهد شد.