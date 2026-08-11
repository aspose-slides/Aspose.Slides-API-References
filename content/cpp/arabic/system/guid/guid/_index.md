---
title: Guid()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كائنًا يمثل GUID مكوّنًا من جميع الأصفار.
type: docs
weight: 1
url: /ar/system/guid/guid/
---
## Guid::Guid() مُنشئ

ينشئ كائنًا يمثل GUID مكوّنًا من جميع الصفر.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) مُنشئ

ينشئ كائنًا يمثل GUID محددًا كمصفوفة من القيم الصحيحة غير الموقعة 8-بت.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | مصفوفة بايت تحتوي على بايتات منفصلة للمعرف GUID |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) مُنشئ

ينشئ كائنًا يمثل GUID محددًا كعرض مصفوفة من القيم الصحيحة غير الموقعة 8-بت.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | مصفوفة بايت تحتوي على بايتات منفصلة للمعرف GUID |

## Guid::Guid(const String\&) مُنشئ

ينشئ كائنًا يمثل GUID محددًا كسلسلة نصية.

```cpp
System::Guid::Guid(const String &g)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| g | const [String](../../string/)\& | تمثيل السلسلة النصية لـ GUID ليُمثَّل بواسطة الكائن الذي يجري إنشاؤه |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) مُنشئ

ينشئ نسخة من الفئة [Guid](../) من مكوّنات GUID المحددة.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | **int32_t** | البتات 0-31 من GUID |
| b | **int16_t** | البتات 32-47 من GUID |
| c | **int16_t** | البتات 48-63 من GUID |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | مصفوفة بايت تحتوي على البتات 64-127 من GUID |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) مُنشئ

ينشئ نسخة من الفئة [Guid](../) من مكوّنات GUID المحددة.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | **int32_t** | البتات 0-31 من GUID |
| b | **int16_t** | البتات 32-47 من GUID |
| c | **int16_t** | البتات 48-63 من GUID |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | عرض مصفوفة بايت يحتوي على البتات 64-127 من GUID |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) مُنشئ

ينشئ نسخة من الفئة [Guid](../) من الأعداد الصحيحة غير الموقعة والبايتات المحددة.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | **int32_t** | البتات 0-31 من GUID |
| b | **int16_t** | البتات 32-47 من GUID |
| c | **int16_t** | البتات 48-63 من GUID |
| d | **uint8_t** | البتات 64-71 من GUID |
| e | **uint8_t** | البتات 72-79 من GUID |
| f | **uint8_t** | البتات 80-87 من GUID |
| g | **uint8_t** | البتات 88-95 من GUID |
| h | **uint8_t** | البتات 96-103 من GUID |
| i | **uint8_t** | البتات 104-111 من GUID |
| j | **uint8_t** | البتات 112-119 من GUID |
| k | **uint8_t** | البتات 120-127 من GUID |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) مُنشئ

ينشئ نسخة من الفئة [Guid](../) من الأعداد الصحيحة غير الموقعة والبايتات المحددة.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | **uint32_t** | البتات 0-31 من GUID |
| b | **uint16_t** | البتات 32-47 من GUID |
| c | **uint16_t** | البتات 48-63 من GUID |
| d | **uint8_t** | البتات 64-71 من GUID |
| e | **uint8_t** | البتات 72-79 من GUID |
| f | **uint8_t** | البتات 80-87 من GUID |
| g | **uint8_t** | البتات 88-95 من GUID |
| h | **uint8_t** | البتات 96-103 من GUID |
| i | **uint8_t** | البتات 104-111 من GUID |
| j | **uint8_t** | البتات 112-119 من GUID |
| k | **uint8_t** | البتات 120-127 من GUID |

## Guid::Guid(const Guid\&) مُنشئ

ينشئ كائنًا يمثل نفس GUID كما هو في الكائن المحدد.

```cpp
System::Guid::Guid(const Guid &guid)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| guid | const [Guid](../)\& | الكائن [Guid](../) لنسخ قيمة GUID منه |

## انظر أيضًا

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Guid](../)
* Class [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)