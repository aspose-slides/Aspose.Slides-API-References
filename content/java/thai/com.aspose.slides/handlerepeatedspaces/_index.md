---
title: HandleRepeatedSpaces
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุวิธีการจัดการกับอักขระช่องว่างธรรมดาที่ซ้ำกันระหว่างการส่งออก Markdown.
type: docs
url: /th/com.aspose.slides/handlerepeatedspaces/
---
**Inheritance:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

ระบุวิธีการจัดการกับอักขระช่องว่างธรรมดาซ้ำที่เกิดขึ้นระหว่างการส่งออก Markdown
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [None](#None) | All spaces are preserved as regular space characters without any changes. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Converts sequences of two or more consecutive regular spaces by alternating between regular space characters and non-breaking space entities NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Converts sequences of two or more consecutive regular spaces by preserving the first space as a regular space character and replacing all subsequent spaces with non-breaking space entities NBSP. |
### None {#None}
```
public static final int None
```

All spaces are preserved as regular space characters without any changes. No transformation is applied, and multiple consecutive spaces are exported as-is.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Converts sequences of two or more consecutive regular spaces by alternating between regular space characters and non-breaking space entities NBSP. The first space is always preserved as a regular space.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Converts sequences of two or more consecutive regular spaces by preserving the first space as a regular space character and replacing all subsequent spaces with non-breaking space entities NBSP.