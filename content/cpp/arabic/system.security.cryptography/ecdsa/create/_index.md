---
title: Create()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ تنفيذًا افتراضيًا لخوارزمية ECDSA.
type: docs
weight: 131
url: /ar/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() طريقة

ينشئ تنفيذًا افتراضيًا لخوارزمية ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### قيمة الإرجاع

كائن خوارزمية ECDSA.

## ECDsa::Create(const ECCurve\&) طريقة

ينشئ تنفيذًا افتراضيًا لخوارزمية ECDSA مع مفتاح تم إنشاؤه حديثًا على المنحنى المحدد.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | المنحنى المستخدم لإنشاء المفتاح. |

### قيمة الإرجاع

كائن خوارزمية ECDSA.

## ECDsa::Create(const ECParameters\&) طريقة

ينشئ تنفيذًا افتراضيًا لخوارزمية ECDSA باستخدام المعلمات المحددة.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | المعلمات التي تمثل المفتاح. |

### قيمة الإرجاع

كائن خوارزمية ECDSA.

## ECDsa::Create(const String\&) طريقة

ينشئ تنفيذًا مخصصًا لخوارزمية ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | اسم الخوارزمية. |

### قيمة الإرجاع

كائن خوارزمية ECDSA.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ECDsa](../)
* فئة [String](../../../system/string/)
* بنية [ECCurve](../../eccurve/)
* بنية [ECParameters](../../ecparameters/)
* نطاق الاسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)