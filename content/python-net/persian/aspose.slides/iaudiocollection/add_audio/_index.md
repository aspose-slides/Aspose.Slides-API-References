---
title: add_audio method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
یک کپی از فایل صوتی را از یک ارائهٔ دیگر اضافه می‌کند.

### Returns
صوت اضافه شد.

```python
def add_audio(self, audio):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio) | صدای منبع. |

## add_audio(self, stream) {#iorawiobase}
یک فایل صوتی را از جریان ایجاد و به ارائه اضافه می‌کند.

### Returns
صوت اضافه شد.

```python
def add_audio(self, stream):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان برای افزودن صدا. |

## add_audio(self, audio_data) {#bytes}
یک فایل صوتی را از آرایهٔ بایت ایجاد و به ارائه اضافه می‌کند.

### Returns
صوت اضافه شد.

```python
def add_audio(self, audio_data):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| audio_data | **bytes** | بایت‌های صدا. |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
یک فایل صوتی را از جریان ایجاد و به ارائه اضافه می‌کند.

### Returns
صوت اضافه شد.

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان برای افزودن صدا از ویدیو. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/fa/aspose.slides/loadingstreambehavior) | رفتاری که بر روی جریان اعمال خواهد شد. |

### موارد مرتبط
* کلاس [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio)
* کلاس [`IAudioCollection`](/slides/python-net/fa/aspose.slides/iaudiocollection)
* شمارش [`LoadingStreamBehavior`](/slides/python-net/fa/aspose.slides/loadingstreambehavior)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)