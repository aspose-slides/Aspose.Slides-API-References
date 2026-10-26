---
title: Create()
second_title: Aspose.Slides للغة C++ مرجع API
description: ينشئ تنفيذ خوارزمية DSA الافتراضية.
type: docs
weight: 105
url: /ar/system.security.cryptography/dsa/create/
---
## DSA::Create() طريقة

ينشئ تنفيذ الخوارزمية الافتراضية [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### قيمة الإرجاع

كائن الخوارزمية [DSA](../).

## DSA::Create(const String\&) طريقة

ينشئ تنفيذ الخوارزمية الافتراضية [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | يجب أن يكون "System.Security.Cryptography.DSACryptoServiceProvider". |

### قيمة الإرجاع

كائن الخوارزمية [DSA](../).

## DSA::Create(int32_t) طريقة

ينشئ تنفيذ الخوارزمية الافتراضية [DSA](../) مع حجم المفتاح المحدد.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | حجم المفتاح، بالبتات. |

## DSA::Create(const DSAParameters\&) طريقة

ينشئ تنفيذ الخوارزمية الافتراضية [DSA](../) مع المعلمات المحددة.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | البارامترات الخاصة بالخوارزمية [DSA](../). |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [DSA](../)
* فئة [String](../../../system/string/)
* بنية [DSAParameters](../../dsaparameters/)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)