---
title: "System::Net::Security"
second_title: "مرجع API Aspose.Slides برای C++"
description: 
type: docs
weight: 716
url: /fa/system.net.security/
---
## کلاس‌ها

| کلاس | توضیح |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | متدهای انتقال اعتبارها در یک جریان را شامل می‌شود. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات تأیید می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید. |
| [SslStream](./sslstream/) | جریانی که از پروتکل SSL برای تأیید هویت سرور و به‌صورت انتخابی مشتری استفاده می‌کند. |

## Enum‌ها

| Enum | توضیح |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | پرچم‌های احراز هویت مخصوص WebRequest. |
| [SslPolicyErrors](./sslpolicyerrors/) | خطاهای سیاست SSL را فهرست می‌کند. |
| [EncryptionPolicy](./encryptionpolicy/) | سیاست‌های رمزنگاری را فهرست می‌کند. |

## Typedef‌ها

| Typedef | توضیح |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | یک بازنمایی کاربری که برای تأیید گواهی SSL راه دور استفاده می‌شود. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | یک بازنمایی کاربری که برای انتخاب گواهی SSL محلی استفاده می‌شود. |