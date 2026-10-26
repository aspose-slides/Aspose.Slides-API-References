---
title: Char
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ให้เมธอดสำหรับการจัดการอักขระที่แสดงเป็นหน่วยรหัส UTF-16 นี้เป็นประเภท static ที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใดก็ตาม.
type: docs
weight: 170
url: /th/system/char/
---
## Char คลาส

ให้เมธอดสำหรับการจัดการอักขระที่แสดงเป็นหน่วยรหัส UTF-16. นี้เป็นประเภท static ที่ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใดก็ตาม.

```cpp
class Char
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | แปลงหน่วยรหัส UTF-32 ให้เป็นอินสแตนซ์ของคลาส [System::String](../string/). |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | แปลงคู่ surrogate UTF-16 ที่ระบุให้เป็นหน่วยรหัส UTF-32. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | แปลงค่าของอักขระที่เข้ารหัสเป็น UTF-16 หรือคู่ surrogate ที่ตำแหน่งที่ระบุในสตริงให้เป็นหน่วยรหัส UTF-32. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | แปลงอักขระ UTF-16 ที่ระบุให้เป็นค่าตัวเลขแบบจุดลอยตัวความแม่นยำคู่. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | คืนค่าแทนหมวดหมู่ Unicode ของอักขระที่ระบุ. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | กำหนดว่าตัวอักขระที่ระบุจัดเป็นอักขระช่องว่าง ASCII หรือไม่. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุจัดเป็นอักขระควบคุม Unicode หรือไม่. |
| static **bool** [IsControl](./iscontrol/)(char_t) | กำหนดว่าตัวอักขระที่ระบุจัดเป็นอักขระควบคุม Unicode หรือไม่. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุจัดเป็นตัวเลขฐานสิบหรือไม่. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในสตริงที่ระบุจัดเป็นตัวเลขฐานสิบหรือไม่. |
| static **bool** [IsDigit](./isdigit/)(char_t) | กำหนดว่าตัวอักขระที่ระบุจัดเป็นตัวเลขฐานสิบหรือไม่. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในสตริงที่ระบุเป็นหน่วยรหัส high surrogate ของ UTF-16 หรือไม่. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุเป็น high surrogate หรือไม่. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | กำหนดว่าตัวอักขระที่ระบุเป็น high surrogate หรือไม่. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุจัดเป็นอักขระตัวอักษร Unicode หรือไม่. |
| static **bool** [IsLetter](./isletter/)(char_t) | กำหนดว่าตัวอักขระที่ระบุจัดเป็นอักขระตัวอักษร Unicode หรือไม่. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุจัดเป็นอักขระตัวอักษร Unicode หรือเป็นตัวเลขฐานสิบหรือไม่. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | กำหนดว่าตัวอักขระที่ระบุจัดเป็นอักขระตัวอักษร Unicode หรือเป็นตัวเลขฐานสิบหรือไม่. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุจัดเป็นอักขระตัวอักษรตัวพิมพ์เล็กหรือไม่. |
| static **bool** [IsLower](./islower/)(char_t) | กำหนดว่าตัวอักขระที่ระบุจัดเป็นอักขระตัวอักษรตัวพิมพ์เล็กหรือไม่. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในสตริงที่ระบุจัดเป็นอักขระตัวอักษรตัวพิมพ์เล็กหรือไม่. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุเป็น low surrogate หรือไม่. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | กำหนดว่าตัวอักขระที่ระบุเป็น low surrogate หรือไม่. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุจัดเป็นตัวเลขหรือไม่. |
| static **bool** [IsNumber](./isnumber/)(char_t) | กำหนดว่าตัวอักขระที่ระบุจัดเป็นตัวเลขหรือไม่. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุจัดเป็นอักขระเครื่องหมายวรรคตอนหรือไม่. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | กำหนดว่าตัวอักขระที่ระบุจัดเป็นอักขระเครื่องหมายวรรคตอนหรือไม่. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุจัดเป็นอักขระตัวแบ่งหรือไม่. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | กำหนดว่าตัวอักขระที่ระบุจัดเป็นอักขระตัวแบ่งหรือไม่. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | กำหนดว่าตัวอักขระที่ระบุเป็นหน่วยรหัส surrogate ของ UTF-16 หรือไม่. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในสตริงที่ระบุเป็นหน่วยรหัส surrogate ของ UTF-16 หรือไม่. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | กำหนดว่าตัวอักขระสองตัวที่ระบุเป็นคู่ surrogate ของ UTF-16 หรือไม่. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | กำหนดว่าตัวอักขระต่อเนื่องสองตัวในบัฟเฟอร์อักขระที่ระบุเป็นคู่ surrogate หรือไม่. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุจัดเป็นอักขระสัญลักษณ์หรือไม่. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | กำหนดว่าตัวอักขระที่ระบุจัดเป็นอักขระสัญลักษณ์หรือไม่. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในสตริงที่ระบุจัดเป็นอักขระตัวอักษรตัวพิมพ์ใหญ่หรือไม่. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุจัดเป็นอักขระตัวอักษรตัวพิมพ์ใหญ่หรือไม่. |
| static **bool** [IsUpper](./isupper/)(char_t) | กำหนดว่าตัวอักขระที่ระบุจัดเป็นอักขระตัวอักษรตัวพิมพ์ใหญ่หรือไม่. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่ระบุจัดเป็นอักขระช่องว่างหรือไม่. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | กำหนดว่าตัวอักขระที่ระบุจัดเป็นอักขระช่องว่างหรือไม่. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | กำหนดว่าตัวอักขระที่ตำแหน่งที่ระบุในสตริงที่ระบุจัดเป็นอักขระช่องว่างหรือไม่. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | แปลงอักขระตัวแรกและตัวเดียวของสตริงที่ระบุเป็นค่า char_t. |
| static char_t [ToLower](./tolower/)(char_t) | แปลงอักขระที่ระบุเป็นตัวพิมพ์เล็ก. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | แปลงอักขระที่ระบุเป็นตัวพิมพ์เล็ก. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | แปลงอักขระที่ระบุเป็นตัวพิมพ์เล็ก. |
| static char_t [ToUpper](./toupper/)(char_t) | แปลงอักขระที่ระบุเป็นตัวพิมพ์ใหญ่. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | แปลงอักขระที่ระบุเป็นตัวพิมพ์ใหญ่. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | แปลงอักขระที่ระบุเป็นตัวพิมพ์ใหญ่. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | พยายามแปลงสตริงที่มีอักขระเดียวเป็นอักขระ UTF-16. ฟังก์ชันจะสำเร็จเฉพาะเมื่อสตริงอินพุตไม่เป็นค่าว่างและมีความยาวเท่ากับหนึ่งอักขระ. |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)