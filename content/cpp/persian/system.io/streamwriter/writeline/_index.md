---
title: WriteLine()
second_title: Aspose.Slides برای مرجع API C++
description: کاراکترهای پایان خط را به جریان می‌نویسد.
type: docs
weight: 92
url: /fa/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() متد

کاراکترهای پایان خط را به جریان می‌نویسد.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) متد

رشتهٔ مشخص‌شده را به همراه کاراکترهای خاتمهٔ خط به جریان می‌نویسد.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | رشته‌ای که باید نوشته شود |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) متد

نمایش رشته‌ای از شیءٔ مشخص‌شده را به همراه کاراکترهای خاتمهٔ خط به جریان می‌نویسد.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | شیئی که باید نوشته شود |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) متد

تمام کاراکترهای موجود در آرایهٔ مشخص‌شده را به همراه کاراکترهای خاتمهٔ خط به جریان می‌نویسد.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | آرایه‌ای که شامل کاراکترهای قابل نوشتن است |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) متد

زیرمحدودهٔ مشخص‌شده‌ای از کاراکترهای UTF-16 در آرایهٔ کاراکتری مشخص‌شده را به همراه کاراکترهای خاتمهٔ خط به جریان می‌نویسد.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | آرایه‌ای که شامل کاراکترهای قابل نوشتن است |
| index | **int32_t** | یک اندیس صفر-محور در **buffer** که زنگام زیرمحدودهٔ قابل نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد کاراکترهای موجود در زیرمحدودهٔ قابل نوشتن؛ -1 به این معناست که زیرمحدوده تا انتهای آرایهٔ **buffer** ادامه دارد |

## StreamWriter::WriteLine(const char_t *) متد

رشتهٔ C-String مشخص‌شده را به همراه کاراکترهای خاتمهٔ خط به جریان می‌نویسد.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const char_t * | رشتهٔ C-String که باید نوشته شود |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) متد

نمایش رشته‌ای از شیءٔ مشخص‌شده را به همراه کاراکترهای خاتمهٔ خط به جریان می‌نویسد.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | شیئی که باید نوشته شود |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [StreamWriter](../)
* کلاس [String](../../../system/string/)
* کلاس [Object](../../../system/object/)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)