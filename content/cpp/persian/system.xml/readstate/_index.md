---
title: ReadState
second_title: Aspose.Slides برای C++ مرجع API
description: وضعیت خواننده را مشخص می‌کند.
type: docs
weight: 703
url: /fa/system.xml/readstate/
---
## enum ReadState

وضعیت خواننده را مشخص می‌کند.

```cpp
enum class ReadState
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| Initial | 0 | متد [XmlReader::Read](../xmlreader/read/) فراخوانی نشده است. |
| Interactive | 1 | متد [XmlReader::Read](../xmlreader/read/) فراخوانی شده است. متدهای اضافی ممکن است روی خواننده فراخوانی شوند. |
| Error | 2 | خطایی رخ داده است که ادامه عملیات خواندن را به‌هم می‌زند. |
| EndOfFile | 3 | به‌درستی به انتهای فایل رسیده است. |
| Closed | 4 | متد [XmlReader::Close](../xmlreader/close/) فراخوانی شده است. |

## موارد مرتبط

* فضای نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)