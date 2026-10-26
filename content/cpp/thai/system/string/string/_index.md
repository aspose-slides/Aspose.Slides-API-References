---
title: String()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คอนสตรัคเตอร์เริ่มต้น สร้างอ็อบเจกต์ string ที่ถือว่าเป็นค่าว่าง
type: docs
weight: 14
url: /th/system/string/string/
---
## String::String() คอนสตรัคเตอร์

คอนสตรัคเตอร์เริ่มต้น สร้างอ็อบเจกต์ string ที่ถือว่าเป็นค่าว่าง

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) คอนสตรัคเตอร์

สร้าง string ตามสตริงลิเทอรัล ถือว่าสตริงลิเทอรัลเป็นสตริงที่จบด้วย null และคำนวนความยาวของสตริงเป้าหมายตามขนาดของลิเทอรัล

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | T\& | [String](../) literal pointer. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) คอนสตรัคเตอร์

สร้าง string ตาม pointer ของสตริงอักขระ ถือว่าเป็นสตริงที่จบด้วย null และคำนวนความยาวของสตริงเป้าหมายตามอักขระ null

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Character string pointer. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) คอนสตรัคเตอร์

สร้าง string ตามสตริงลิเทอรัล ถือว่าสตริงลิเทอรัลเป็นสตริงที่จบด้วย null ใน UTF-8 และคำนวนความยาวของสตริงเป้าหมายตามขนาดของลิเทอรัล

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | T\& | [String](../) literal pointer. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) คอนสตรัคเตอร์

สร้าง string ตาม pointer ของสตริงอักขระ ถือว่าเป็นสตริงที่จบด้วย null ใน UTF-8 และคำนวนความยาวของสตริงเป้าหมายตามอักขระ null

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Character string pointer. |

## String::String(const char16_t *, int) คอนสตรัคเตอร์

สร้าง string จาก pointer ของสตริงอักขระและความยาวที่กำหนดโดยชัดเจน

```cpp
System::String::String(const char16_t *str, int length)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char16_t * | [String](../) pointer, may be literal or array. |
| length | int | Explicit string length |

## String::String(const ReadOnlySpan\<char16_t\>\&) คอนสตรัคเตอร์

กำหนดค่าเฉพาะของคลาส [System.String](../) ด้วยอักขระ Unicode ที่ระบุใน read-only span

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | A read-only span of Unicode characters. |

## String::String(const char *, int) คอนสตรัคเตอร์

สร้าง string จาก pointer ของสตริงอักขระและความยาวที่กำหนดโดยชัดเจน

```cpp
System::String::String(const char *str, int length)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char * | [String](../) pointer to the UTF8 data, may be literal or array. |
| length | int | Explicit string length |

## String::String(const char16_t *, int, int) คอนสตรัคเตอร์

สร้าง string จาก pointer ของสตริงอักขระโดยเริ่มจากตำแหน่งเริ่มต้นและใช้ความยาวที่ระบุ

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char16_t * | [String](../) pointer, may be literal or array. |
| start | int | Starting position. |
| length | int | [String](../) length. |

## String::String(const char16_t, int) คอนสตรัคเตอร์

คอนสตรัคเตอร์เติมค่า

```cpp
System::String::String(const char16_t ch, int count)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| ch | const char16_t | Fill character. |
| count | int | Target length. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) คอนสตรัคเตอร์

คอนสตรัคเตอร์ nullptr ประกาศเป็นเทมเพลตเพื่อจัดลำดับความสำคัญกับคอนสตรัคเตอร์เทมเพลตอื่น

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T | Should be nullptr_t |

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) คอนสตรัคเตอร์

สร้าง string ตาม widestring literal ถือว่าสตริงลิเทอรัลเป็นสตริงที่จบด้วย null และคำนวนความยาวของสตริงเป้าหมายตามขนาดของลิเทอรัล การแปลงจาก **wchar_t** ใช้เวลานานบนแพลตฟอร์มบางตัว จึงไม่อนุญาตให้แปลงโดยอัตโนมัติ

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | T\& | [String](../) literal pointer. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) คอนสตรัคเตอร์

สร้าง string ตาม pointer ของสตริงอักขระกว้าง ถือว่าเป็นสตริงที่จบด้วย null และคำนวนความยาวของสตริงเป้าหมายตามอักขระ null การแปลงจาก **wchar_t** ใช้เวลานานบนแพลตฟอร์มบางตัว จึงไม่อนุญาตให้แปลงโดยอัตโนมัติ

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Character string pointer. |

## String::String(const wchar_t *, int) คอนสตรัคเตอร์

สร้าง string จาก pointer ของสตริงอักขระกว้างและความยาวที่กำหนดโดยชัดเจน การแปลงจาก **wchar_t** ใช้เวลานานบนแพลตฟอร์มบางตัว จึงไม่อนุญาตให้แปลงโดยอัตโนมัติ

```cpp
System::String::String(const wchar_t *str, int length)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) pointer, may be literal or array. |
| length | int | Explicit string length |

## String::String(const wchar_t, int) คอนสตรัคเตอร์

คอนสตรัคเตอร์เติมค่า การแปลงจาก **wchar_t** ใช้เวลานานบนแพลตฟอร์มบางตัว จึงไม่อนุญาตให้แปลงโดยอัตโนมัติ

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| ch | const **wchar_t** | Fill character. |
| count | int | Target length. |

## String::String(const String\&) คอนสตรัคเตอร์

คอนสตรัคเตอร์คัดลอก

```cpp
System::String::String(const String &str)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) to copy. |

## String::String(String\&&) คอนสตรัคเตอร์

คอนสตรัคเตอร์ย้าย

```cpp
System::String::String(String &&str) noexcept
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) to move data from. |

## String::String(const ArrayPtr\<char16_t\>\&) คอนสตรัคเตอร์

แปลงอาร์เรย์อักขระทั้งหมดเป็น string

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) to convert to string. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) คอนสตรัคเตอร์

แปลงช่วงย่อยของอาร์เรย์อักขระเป็น string หากพารามิเตอร์อยู่นอกขอบเขตของอาร์เรย์ จะสร้าง string ว่าง

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Character array. |
| offset | int | Subarray start index. |
| len | int | Subarray length. |

## String::String(const codeporting_icu::UnicodeString\&) คอนสตรัคเตอร์

ห่อ **UnicodeString** เข้าใน [String](../)

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString to wrap into [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) คอนสตรัคเตอร์

คอนสตรัคเตอร์ย้าย

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString to wrap into [String](../). |

## String::String(const std::wstring\&) คอนสตรัคเตอร์

สร้าง [String](../) จาก widestring

```cpp
System::String::String(const std::wstring &str)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const std::wstring\& | Widestring to convert into [String](../). |

## String::String(const std::u16string\&) คอนสตรัคเตอร์

สร้าง [String](../) จาก string utf16

```cpp
System::String::String(const std::u16string &str)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const std::u16string\& | Utf16 string to convert into [String](../). |

## String::String(const std::string\&) คอนสตรัคเตอร์

สร้าง [String](../) จาก std::string ที่อยู่ในรูปแบบ UTF-8

```cpp
System::String::String(const std::string &utf8str)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| utf8str | const std::string\& | std::string string to convert into [String](../). |

## String::String(const std::u32string\&) คอนสตรัคเตอร์

สร้าง [String](../) จาก std::u32string

```cpp
System::String::String(const std::u32string &u32str)
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string string to convert into [String](../). |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [ReadOnlySpan](../../readonlyspan/)
* Struct [IsStringLiteral](../../isstringliteral/)
* Struct [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)