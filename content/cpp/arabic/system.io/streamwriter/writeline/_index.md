---
title: WriteLine()
second_title: Aspose.Slides لـ C++ مرجع API
description: يكتب أحرف إنهاء السطر إلى المجرى.
type: docs
weight: 92
url: /ar/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() طريقة

يكتب أحرف إنهاء السطر إلى المجرى.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) طريقة

يكتب السلسلة المحددة متبوعةً بأحرف إنهاء السطر إلى المجرى.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | السلسلة المراد كتابتها |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) طريقة

يكتب تمثيل السلسلة للكائن المحدد متبوعاً بأحرف إنهاء السطر إلى المجرى.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | الكائن المراد كتابته |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) طريقة

يكتب جميع الأحرف من المصفوفة المحددة متبوعةً بأحرف إنهاء السطر إلى المجرى.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | المصفوفة التي تحتوي على الأحرف المراد كتابتها |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من أحرف UTF-16 من المصفوفة المحددة متبوعاً بأحرف إنهاء السطر إلى المجرى.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | المصفوفة التي تحتوي على الأحرف المراد كتابتها |
| index | **int32_t** | مؤشر يبدأ من الصفر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | **int32_t** | عدد الأحرف في النطاق الفرعي للكتابة؛ -1 يعني أن النطاق ينتهي عند نهاية مصفوفة **buffer** |

## StreamWriter::WriteLine(const char_t *) طريقة

يكتب سلسلة C المحددة متبوعةً بأحرف إنهاء السطر إلى المجرى.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const char_t * | سلسلة C المراد كتابتها |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) طريقة

يكتب تمثيل السلسلة للكائن المحدد متبوعاً بأحرف إنهاء السطر إلى المجرى.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الكائن |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | الكائن المراد كتابته |

## أنظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)