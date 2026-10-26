---
title: ResourceLoadingAction
second_title: Aspose.Slides สำหรับ Java API Reference
description: ระบุโหมดการโหลดทรัพยากรภายนอก.
type: docs
url: /th/com.aspose.slides/resourceloadingaction/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

ระบุโหมดการโหลดทรัพยากรภายนอก.
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [Default](#Default) | Aspose.Slides จะโหลดทรัพยากรภายนอกตามปกติ. |
| [Skip](#Skip) | Aspose.Slides จะข้ามการโหลดทรัพยากรภายนอก. |
| [UserProvided](#UserProvided) | Aspose.Slides จะใช้ byte array ที่ผู้ใช้ให้ใน [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) เป็นข้อมูลภาพ. |
### Default {#Default}
```
public static final int Default
```

Aspose.Slides จะโหลดทรัพยากรภายนอกตามปกติ.

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides จะข้ามการโหลดทรัพยากรภายนอก. ลิงก์ที่ไม่มีข้อมูลจะถูกจัดเก็บสำหรับภาพเท่านั้น.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides จะใช้ byte array ที่ผู้ใช้ให้ใน [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) เป็นข้อมูลภาพ.