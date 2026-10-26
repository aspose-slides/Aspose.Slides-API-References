---
title: CipherMode
second_title: Aspose.Slides برای C++ مرجع API
description: حالت رمز بلوکی.
type: docs
weight: 885
url: /fa/system.security.cryptography/ciphermode/
---
## CipherMode enum

Block cipher mode.

```cpp
enum class CipherMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| CBC | 1 | زنجیره‌سازی بلوک‌های رمز که بلوک فعلی را با بلوک قبلی ترکیب می‌کند تا رمزنگاری بهبود یابد. |
| ECB | 2 | حالت دفترچه کد الکترونیکی که هیچ تأثیر بین بلوک‌ها ندارد؛ منجر به رمزنگاری ضعیف‌تر می‌شود. |
| OFB | 3 | حالت بازخورد خروجی که بلوک‌های ورودی بزرگ را به صورت قطعات کوچک پردازش می‌کند. |
| CFB | 4 | حالت بازخورد رمز که بلوک‌های ورودی بزرگ را به صورت قطعات کوچک پردازش می‌کند. قواعد مخدوش‌سازی با OFB متفاوت است. |
| CTS | 5 | حالت سرقت متن رمز، مشابه CBC عمل می‌کند به جز دو بلوک آخر متن. |

## موارد مرتبط

* فضای نام [System::Security::Cryptography](../)
* کتابخانه [Aspose.Slides](../../)