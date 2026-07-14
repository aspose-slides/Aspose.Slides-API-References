---
title: HandleRepeatedSpaces
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: ระบุวิธีการจัดการอักขระช่องว่างธรรมดาที่ซ้ำกันระหว่างการส่งออกเป็น Markdown.
type: docs
url: /th/com.aspose.slides/handlerepeatedspaces/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

ระบุวิธีการจัดการอักขระช่องว่างธรรมดาที่ซ้ำกันระหว่างการส่งออกเป็น Markdown.

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [None](#None) | ช่องว่างทั้งหมดจะถูกเก็บไว้เป็นอักขระช่องว่างธรรมดาโดยไม่มีการเปลี่ยนแปลงใด ๆ |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | แปลงลำดับของช่องว่างธรรมดาที่ต่อเนื่องกันสองตัวหรือมากกว่าโดยสลับระหว่างอักขระช่องว่างธรรมดาและเอนทิตีไม่ตัดบรรทัด (NBSP) |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | แปลงลำดับของช่องว่างธรรมดาที่ต่อเนื่องกันสองตัวหรือมากกว่าโดยเก็บช่องว่างแรกเป็นอักขระช่องว่างธรรมดาและเปลี่ยนช่องว่างที่ตามมาทั้งหมดเป็นเอนทิตีไม่ตัดบรรทัด (NBSP) |

### None {#None}
```
public static final int None
```

ช่องว่างทั้งหมดจะถูกเก็บไว้เป็นอักขระช่องว่างธรรมดาโดยไม่มีการเปลี่ยนแปลงใด ๆ ไม่ได้ทำการแปลงใด ๆ และช่องว่างต่อเนื่องหลายตัวจะถูกส่งออกตามเดิม

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

แปลงลำดับของช่องว่างธรรมดาที่ต่อเนื่องกันสองตัวหรือมากกว่าโดยสลับระหว่างอักขระช่องว่างธรรมดาและเอนทิตีไม่ตัดบรรทัด (NBSP) ช่องว่างตัวแรกจะถูกเก็บไว้เป็นช่องว่างธรรมดาตลอด

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

แปลงลำดับของช่องว่างธรรมดาที่ต่อเนื่องกันสองตัวหรือมากกว่าโดยเก็บช่องว่างแรกเป็นอักขระช่องว่างธรรมดาและเปลี่ยนช่องว่างที่ตามมาทั้งหมดเป็นเอนทิตีไม่ตัดบรรทัด (NBSP)