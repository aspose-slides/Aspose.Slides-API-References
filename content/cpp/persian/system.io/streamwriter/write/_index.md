---
title: Write()
second_title: مرجع API Aspose.Slides برای C++
description: کاراکتر مشخص‌شده را در جریان می‌نویسد.
type: docs
weight: 79
url: /fa/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) متد

کاراکتر مشخص‌شده را در جریان می‌نویسد.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char_t | کاراکتری که باید نوشته شود |

## StreamWriter::Write(const String\&) متد

رشتهٔ مشخص‌شده را در جریان می‌نویسد.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | رشته‌ای که باید نوشته شود |

## StreamWriter::Write(const SharedPtr\<Object\>\&) متد

نمایش رشته‌ای از شیء مشخص‌شده را در جریان می‌نویسد.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | شیئی که باید نوشته شود |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) متد

تمام کاراکترها را از آرایهٔ مشخص‌شده در جریان می‌نویسد.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | آرایه‌ای که شامل کاراکترهای مورد نوشتن است |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) متد

بخش مشخص‌شده‌ای از کاراکترهای UTF-16 را از آرایهٔ کاراکتری مشخص به جریان می‌نویسد.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | آرایه‌ای که شامل کاراکترهای مورد نوشتن است |
| index | **int32_t** | یک ایندکس صفر-مبنا از عنصر در **buffer** که بازهٔ زیرنویس برای نوشتن از آن آغاز می‌شود |
| count | **int32_t** | تعداد کاراکترهای موجود در بازهٔ زیرنویس برای نوشتن؛ -1 به معنای این است که بازه تا پایان آرایهٔ **buffer** ادامه دارد |

## StreamWriter::Write(const char_t *) متد

رشتهٔ C-null-پایان‌دار مشخص‌شده را در جریان می‌نویسد.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const char_t * | رشتهٔ C-null-پایان‌دار که باید نوشته شود |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) متد

نمایش رشته‌ای از شیء مشخص‌شده را در جریان می‌نویسد.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```

### Template parameters

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | شیئی که باید نوشته شود |

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [StreamWriter](../)
* کلاس [String](../../../system/string/)
* کلاس [Object](../../../system/object/)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)