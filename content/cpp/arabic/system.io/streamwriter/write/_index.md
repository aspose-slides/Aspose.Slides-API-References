---
title: Write()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يكتب الحرف المحدد إلى الدفق.
type: docs
weight: 79
url: /ar/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) طريقة

يكتب الحرف المحدد إلى الدفق.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | char_t | الحرف الذي سيتم كتابته |

## StreamWriter::Write(const String\&) طريقة

يكتب السلسلة المحددة إلى الدفق.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | السلسلة التي سيتم كتابتها |

## StreamWriter::Write(const SharedPtr\<Object\>\&) طريقة

يكتب تمثيل النص للكائن المحدد إلى الدفق.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | الكائن الذي سيتم كتابته |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) طريقة

يكتب جميع الأحرف من المصفوفة المحددة إلى الدفق.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | المصفوفة التي تحتوي على الأحرف التي سيتم كتابتها |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من أحرف UTF-16 من المصفوفة المحددة إلى الدفق.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | المصفوفة التي تحتوي على الأحرف التي سيتم كتابتها |
| index | **int32_t** | مؤشر مبني على صفر للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | **int32_t** | عدد الأحرف في النطاق الفرعي للكتابة؛ -1 يحدد أن النطاق الفرعي ينتهي عند نهاية مصفوفة **buffer** |

## StreamWriter::Write(const char_t *) طريقة

يكتب السلسلة C المحددة إلى الدفق.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | const char_t * | السلسلة C التي سيتم كتابتها |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) طريقة

يكتب تمثيل النص للكائن المحدد إلى الدفق.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```

### معامل القالب

| معامل | الوصف |
| --- | --- |
| T | نوع الكائن |

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | الكائن الذي سيتم كتابته |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [StreamWriter](../)
* فئة [String](../../../system/string/)
* فئة [Object](../../../system/object/)
* مساحة الاسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)