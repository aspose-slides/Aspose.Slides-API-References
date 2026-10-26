---
title: RegexOptions
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตัวเลือก Regex.
type: docs
weight: 118
url: /th/system.text.regularexpressions/regexoptions/
---
## RegexOptions enum


[Regex](../regex/) ตัวเลือก.

```cpp
enum class RegexOptions
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| None | 0 | พฤติกรรมเริ่มต้น. |
| Compiled | 1 | คอมไพล์ regex เพื่อประสิทธิภาพ. ทำโดยอัตโนมัติเสมอ. |
| CultureInvariant | 2 | ใช้การจับคู่แบบไม่ขึ้นกับวัฒนธรรม. ถูกละเว้น. |
| ECMAScript | 4 | ใช้ไวยากรณ์ ECMAScript. ถูกละเว้น. |
| ExplicitCapture | 8 | จับภาพแบบชัดเจนเท่านั้น. ถูกละเว้น. |
| IgnoreCase | 16 | ไม่สนใจตัวพิมพ์เล็กใหญ่ขณะจับคู่. |
| IgnorePatternWhitespace | 32 | ละเว้นช่องว่างในแพทเทิร์น. ไม่รองรับ. |
| Multiline | 64 | ถือว่า '^' และ '$' เป็นจุดเริ่มต้นและสิ้นสุดของบรรทัด, ไม่ใช่ทั้งสตริง. |
| RightToLeft | 128 | การจับคู่จากขวาไปซ้าย. ไม่รองรับ. |
| Singleline | 256 | ทำให้ '.' จับคู่กับอักขระใดก็ได้โดยไม่มีข้อยกเว้น (โดยปกติอักขระขึ้นบรรทัดใหม่จะไม่ถูกจับคู่). |

## ดูเพิ่มเติม

* เนมส페ซ [System::Text::RegularExpressions](../)
* ไลบรารี [Aspose.Slides](../../)