---
title: PresentationLockingBehavior
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงพฤติกรรมที่เกี่ยวกับการจัดการไฟล์แหล่งข้อมูลหรือ java.io.InputStream ขณะโหลดและทำงานกับอินสแตนซ์ของ .
type: docs
url: /th/com.aspose.slides/presentationlockingbehavior/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

แสดงพฤติกรรมที่เกี่ยวกับการจัดการ [IPresentation](../../com.aspose.slides/ipresentation) แหล่งข้อมูล (ไฟล์หรือ java.io.InputStream) ขณะโหลดและทำงานกับอินสแตนซ์ของ [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

แหล่งข้อมูลเป็นพารามิเตอร์ที่ส่งให้กับคอนสตรัคเตอร์ [IPresentation](../../com.aspose.slides/ipresentation) ส่วนในตัวอย่างด้านล่าง แหล่งข้อมูลคือไฟล์ "pres.pptx": สำหรับตัวอย่างนี้ แหล่งข้อมูล ("pres.pptx" file) จะถูกล็อคตลอดอายุของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) นั่นหมายความว่าไม่สามารถเปลี่ยนแปลงหรือทำลายโดยกระบวนการอื่นได้.
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | แหล่งข้อมูลจะถูกล็อคเฉพาะระหว่างการทำงานของคอนสตรัคเตอร์ [IPresentation](../../com.aspose.slides/ipresentation) เท่านั้น. |
| [KeepLocked](#KeepLocked) | แหล่งข้อมูลจะถูกล็อคตลอดอายุของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) จนกระทั่งมันถูกทำลาย. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

แหล่งข้อมูลจะถูกล็อคเฉพาะระหว่างการทำงานของคอนสตรัคเตอร์ [IPresentation](../../com.aspose.slides/ipresentation) เท่านั้น.

--------------------

หาก ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) ตั้งค่าเป็น false, BLOB ทั้งหมดจะถูกโหลดเข้าสำมิวนต์ หากไม่เช่นนั้น อาจใช้วิธีอื่นเช่นไฟล์ชั่วคราว.

--------------------

พฤติกรรมนี้ทำงานช้ากว่า [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) และหากเป็นไปได้ที่จะส่งมอบความเป็นเจ้าของของแหล่งข้อมูลให้กับ [IPresentation](../../com.aspose.slides/ipresentation) แนะนำให้ใช้ [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

แหล่งข้อมูลจะถูกล็อคตลอดอายุของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) จนกระทั่งมันถูกทำลาย.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) ต้องตั้งค่าเป็น true เพื่อใช้พฤติกรรมนี้ มิฉะนั้นจะเกิดข้อยกเว้น.

--------------------

พฤติกรรมนี้แนะนำ เนื่องจากทำงานเร็วกว่าและใช้หน่วยความจำน้อยกว่า [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).