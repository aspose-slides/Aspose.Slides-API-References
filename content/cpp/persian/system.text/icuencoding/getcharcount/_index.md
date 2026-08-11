---
title: GetCharCount()
second_title: مرجع API Aspose.Slides برای C++
description: تعداد کاراکترهای مورد نیاز برای رمزگشایی یک بافر بایت را برمی‌گرداند.
type: docs
weight: 53
url: /fa/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) متد


Get the number of characters needed to decode a byte buffer.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### مقدار بازگشت

Number of characters.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) متد


Get the number of characters needed to decode a byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| index | int | Slice beginning. |
| count | int | Slice size. |

### مقدار بازگشت

Number of characters.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) متد


Get the number of characters needed to decode a byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |

### مقدار بازگشت

Number of characters.

## ICUEncoding::GetCharCount(const uint8_t *, int) متد


Get the number of characters needed to decode a byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### مقدار بازگشت

Number of characters.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)