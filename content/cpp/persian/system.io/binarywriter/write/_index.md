---
title: Write()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار صحیح بدون علامت ۸ بیتی مشخص‌شده را در جریان خروجی می‌نویسد.
type: docs
weight: 92
url: /fa/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) متد

Writes the specified unsigned 8-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **uint8_t** | مقدار برای نوشتن |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) متد

Writes the specified subrange of bytes from the specified byte array to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای که بایت‌های قابل نوشتن را شامل می‌شود |
| index | int | یک نمایه صفر-پایه از عنصر در **buffer** که بخش نوشتن از آن آغاز می‌شود |
| count | int | تعداد عناصر در بخش نوشتن؛ -1 به معنای این است که بخش تا انتهای آرایه **buffer** ادامه پیدا می‌کند |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) متد

Writes the specified subrange of UTF-16 characters from the specified character array to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | آرایه‌ای که کاراکترهای قابل نوشتن را شامل می‌شود |
| index | int | یک نمایه صفر-پایه از عنصر در **buffer** که بخش نوشتن از آن آغاز می‌شود |
| count | int | تعداد کاراکترها در بخش نوشتن؛ -1 به معنای این است که بخش تا انتهای آرایه **buffer** ادامه پیدا می‌کند |

## BinaryWriter::Write(bool) متد

Writes single byte with a value of 0 if **value** is 'true' and 1 if **value** is 'false' to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **bool** | مقدار بولی که مقدار بایت برای نوشتن در جریان خروجی را تعیین می‌کند |

## BinaryWriter::Write(char16_t) متد

Writes the specified 16-bit wide character value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char16_t | مقدار برای نوشتن |

## BinaryWriter::Write(int16_t) متد

Writes the specified 16-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **int16_t** | مقدار برای نوشتن |

## BinaryWriter::Write(int) متد

Writes the specified 32-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int | مقدار برای نوشتن |

## BinaryWriter::Write(int64_t) متد

Writes the specified 64-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **int64_t** | مقدار برای نوشتن |

## BinaryWriter::Write(uint16_t) متد

Writes the specified unsigned 16-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **uint16_t** | مقدار برای نوشتن |

## BinaryWriter::Write(uint32_t) متد

Writes the specified unsigned 32-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **uint32_t** | مقدار برای نوشتن |

## BinaryWriter::Write(uint64_t) متد

Writes the specified unsigned 64-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **uint64_t** | مقدار برای نوشتن |

## BinaryWriter::Write(float) متد

Writes the specified single-precision floating point value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **float** | مقدار برای نوشتن |

## BinaryWriter::Write(double) متد

Writes the specified double-precision floating point value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **double** | مقدار برای نوشتن |

## BinaryWriter::Write(const Decimal\&) متد

Writes the byte representation of the specified [Decimal](../../../system/decimal/) value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | مقدار برای نوشتن |

## BinaryWriter::Write(const String\&) متد

Writes a length-prefixed string in the current encoding to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | رشته برای نوشتن |

## BinaryWriter::Write(const char_t *) متد

Writes a length-prefixed string in the current encoding to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const char_t * | رشته C برای نوشتن |

## مراجع

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [BinaryWriter](../)
* کلاس [Decimal](../../../system/decimal/)
* کلاس [String](../../../system/string/)
* فضای نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)