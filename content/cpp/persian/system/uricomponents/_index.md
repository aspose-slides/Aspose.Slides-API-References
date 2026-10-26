---
title: UriComponents
second_title: Aspose.Slides برای C++ مرجع API
description: اجزای URI را نشان می‌دهد.
type: docs
weight: 3251
url: /fa/system/uricomponents/
---
## UriComponents enum

نمایش اجزای URI.

```cpp
enum class UriComponents
```

### Values

| نام | مقدار | توضیح |
| --- | --- | --- |
| Scheme | 1 | داده Scheme. |
| UserInfo | 2 | داده UserInfo. |
| Host | 4 | داده Host. |
| Port | 8 | داده Port. |
| SchemeAndServer | n/a | داده‌های Scheme، Host و Port. |
| Path | 16 | داده LocalPath. |
| Query | 32 | داده Query. |
| PathAndQuery | n/a | داده‌های LocalPath و Query. |
| HttpRequestUrl | n/a | داده‌های Scheme، Host، Port، Query و LocalPath. |
| Fragment | 64 | داده Fragment. |
| AbsoluteUri | n/a | داده‌های Scheme، Host، Port، Quer، LocalPath و Fragment. |
| StrongPort | 128 | داده Port؛ اگر دادهٔ پورت در [Uri](../uri/) موجود نباشد و یک پورت پیش‌فرض به Scheme اختصاص داده شده باشد، پورت پیش‌فرض بازگردانده می‌شود؛ اگر پورت پیش‌فرض وجود نداشته باشد، -1 بازگردانده می‌شود. |
| HostAndPort | n/a | داده Host و Port؛ اگر دادهٔ پورت در [Uri](../uri/) موجود نباشد و یک پورت پیش‌فرض به Scheme اختصاص داده شده باشد، پورت پیش‌فرض بازگردانده می‌شود. اگر پورت پیش‌فرض وجود نداشته باشد، -1 بازگردانده می‌شود. |
| StrongAuthority | n/a | داده UserInfo، Host و Port.اگر دادهٔ پورت در [Uri](../uri/) موجود نباشد و یک پورت پیش‌فرض به Scheme اختصاص داده شده باشد، پورت پیش‌فرض بازگردانده می‌شود.اگر پورت پیش‌فرض وجود نداشته باشد، -1 بازگردانده می‌شود. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | مشخص می‌کند که جداکننده باید گنجانده شود. |
| SerializationInfoString | n/a | متن کامل [Uri](../uri/) که برای Serializers [Uri](../uri/) مورد نیاز است. متن شامل دامنه IPv6 است. |

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)