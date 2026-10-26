---
title: SecurityPermissionFlag
second_title: مرجع API لـ Aspose.Slides للغة C++
description: أعلام أمان الإذن.
type: docs
weight: 27
url: /ar/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum

أعلام أمان الإذن.

```cpp
enum class SecurityPermissionFlag
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| NoFlags | 0 | لا وصول. |
| Assertion | 1 | تأكيد أن الإذن مُعطى. |
| UnmanagedCode | 2 | استدعاء التعليمات البرمجية غير المدارة. |
| SkipVerification | 4 | تخطي التحقق من التعليمات البرمجية. |
| Execution | 8 | تنفيذ التعليمات البرمجية. |
| ControlThread | 16 | إجراء عمليات على المواضيع. |
| ControlEvidence | 32 | التحكم أو تعديل أدلة CLR. |
| ControlPolicy | 64 | عرض وتغيير السياسة. |
| SerializationFormatter | 128 | تسلسل. |
| ControlDomainPolicy | 256 | تعيين سياسة المجال. |
| ControlPrincipal | 512 | التحكم في كائن المبدأ. |
| ControlAppDomain | 1024 | التحكم في نطاق التطبيق. |
| RemotingConfiguration | 2048 | تكوين الإعادة البعيدة. |
| Infrastructure | 4096 | التوصيل ببنية CLR التحتية. |
| BindingRedirects | 8192 | إجراء توجيه ربط صريح. |
| AllFlags | 16383 | غير مقيد. |

## انظر أيضًا

* المساحة [System::Security::Permissions](../)
* المكتبة [Aspose.Slides](../../)