---
title: Write()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بكتابة تمثيل النص للكائن المحدد إلى الدفق.
type: docs
weight: 105
url: /ar/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) طريقة

يقوم بكتابة تمثيل النص للكائن المحدد إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | الكائن للكتابة |

## TextWriter::Write(bool) طريقة

يقوم بكتابة تمثيل النص للقيمة المنطقية المحددة إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **bool** | القيمة المراد كتابتها |

## TextWriter::Write(char_t) طريقة

يقوم بكتابة الحرف المحدد إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char_t | القيمة المراد كتابتها |

## TextWriter::Write(Decimal) طريقة

يقوم بكتابة تمثيل النص للكائن [Decimal](../../../system/decimal/) المحدد إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | الكائن للكتابة |

## TextWriter::Write(double) طريقة

يقوم بكتابة تمثيل النص للقيمة العشرية ذات الدقة المزدوجة المحددة إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **double** | القيمة المراد كتابتها |

## TextWriter::Write(int) طريقة

يقوم بكتابة تمثيل النص للقيمة الصحيحة 32-بت المحددة إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int | القيمة المراد كتابتها |

## TextWriter::Write(int64_t) طريقة

يقوم بكتابة تمثيل النص للقيمة الصحيحة 64-بت المحددة إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **int64_t** | القيمة المراد كتابتها |

## TextWriter::Write(float) طريقة

يقوم بكتابة تمثيل النص للقيمة العائمة ذات الدقة المفردة المحددة إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **float** | القيمة المراد كتابتها |

## TextWriter::Write(const String\&) طريقة

يقوم بكتابة السلسلة المحددة إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | السلسلة للكتابة |

## TextWriter::Write(uint32_t) طريقة

يقوم بكتابة تمثيل النص للقيمة الصحيحة غير الموقعة 32-بت المحددة إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **uint32_t** | القيمة المراد كتابتها |

## TextWriter::Write(uint64_t) طريقة

يقوم بكتابة تمثيل النص للقيمة الصحيحة غير الموقعة 64-بت المحددة إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **uint64_t** | القيمة المراد كتابتها |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) طريقة

يقوم بكتابة جميع الأحرف من المصفوفة المحددة إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | المصفوفة التي تحتوي على الأحرف للكتابة |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) طريقة

يقوم بكتابة النطاق الفرعي المحدد من الأحرف UTF-16 من مصفوفة الأحرف المحددة إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | المصفوفة التي تحتوي على الأحرف للكتابة |
| index | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | **int32_t** | عدد الأحرف في النطاق الفرعي للكتابة؛ -1 يحدد أن النطاق ينتهي حيث تنتهي مصفوفة **buffer** |

## TextWriter::Write(const char_t *) طريقة

يقوم بكتابة السلسلة C المحددة إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const char_t * | السلسلة C للكتابة |

## TextWriter::Write(const TypeInfo\&) طريقة

يقوم بكتابة تمثيل النص للكائن [TypeInfo](../../../system/typeinfo/) المحدد إلى الدفق.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | الكائن للكتابة |

## TextWriter::Write(const String\&, const TArgs\&...) طريقة

يقوم بكتابة القيم المحددة مُنسَّقة وفقًا للتنسيق المحدد إلى الدفق.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```

### معاملـات القالب

| المعامل | الوصف |
| --- | --- |
| TArgs | قائمة الأنواع للقيم المراد كتابتها |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | تنسيق السلسلة |
| args | const TArgs\&... | القيم المراد كتابتها |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [TextWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)