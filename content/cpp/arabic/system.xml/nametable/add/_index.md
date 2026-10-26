---
title: Add()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بتجزئة السلسلة المحددة ويضيفها إلى NameTable.
type: docs
weight: 14
url: /ar/system.xml/nametable/add/
---
## NameTable::Add(const String\&) طريقة

يقوم بتجزئة السلسلة المحددة ويضيفها إلى [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | السلسلة لإضافتها. |

### قيمة الإرجاع

السلسلة التي تم تجزئتها أو السلسلة الموجودة إذا كانت موجودة بالفعل في [NameTable](../).

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) طريقة

يقوم بتجزئة السلسلة المحددة ويضيفها إلى [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | مصفوفة الأحرف التي تحتوي على السلسلة لإضافتها. |
| start | **int32_t** | الفهرس الصفري في المصفوفة الذي يحدد أول حرف من السلسلة. |
| len | **int32_t** | عدد الأحرف في السلسلة. |

### قيمة الإرجاع

السلسلة التي تم تجزئتها أو السلسلة الموجودة إذا كانت موجودة بالفعل في [NameTable](../). إذا كان **len** صفرًا، يتم إرجاع [String::Empty](../../../system/string/empty/).

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [NameTable](../)
* فضاء الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)