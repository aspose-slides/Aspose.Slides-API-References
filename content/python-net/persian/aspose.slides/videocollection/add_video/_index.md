---
title: add_video method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/videocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
یک کپی از یک فایل ویدئویی را از یک ارائه دیگر اضافه می‌کند.

### Returns
ویدئوی اضافه شده.

```python
def add_video(self, video):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/fa/aspose.slides/ivideo) | ویدئوی منبع. |

## add_video(self, video_data) {#bytes}
یک ویدئو را از آرایه بایت ایجاد و به یک ارائه اضافه می‌کند.

### Returns
ویدئوی اضافه شده.

```python
def add_video(self, video_data):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| video_data | **bytes** | بایت‌های ویدئو. |

## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
یک ویدئو را از جریان ایجاد و به یک ارائه اضافه می‌کند.

### Returns
Added [`IVideo`](/slides/python-net/fa/aspose.slides/ivideo).

```python
def add_video(self, stream, loading_stream_behavior):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریانی که فایل ویدئو از آن اضافه می‌شود. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/fa/aspose.slides/loadingstreambehavior) | رفتاری که بر روی جریان اعمال خواهد شد. |

### See Also
* کلاس [`IVideo`](/slides/python-net/fa/aspose.slides/ivideo)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/fa/aspose.slides/loadingstreambehavior)
* کلاس [`VideoCollection`](/slides/python-net/fa/aspose.slides/videocollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)