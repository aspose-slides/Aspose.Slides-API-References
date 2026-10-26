---
title: PresentationLockingBehavior
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงพฤติกรรมที่เกี่ยวกับการจัดการ  source file หรือ  java.io.InputStream ขณะโหลดและทำงานกับอินสแตนซ์ของ .
type: docs
url: /th/com.aspose.slides/presentationlockingbehavior/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

แสดงถึงพฤติกรรมที่เกี่ยวกับการจัดการแหล่งข้อมูล [IPresentation](../../com.aspose.slides/ipresentation) (ไฟล์หรือ java.io.InputStream) ในขณะโหลดและทำงานกับอินสแตนซ์ของ [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

แหล่งข้อมูลเป็นพารามิเตอร์ที่ส่งให้กับคอนสตรัคเตอร์ [IPresentation](../../com.aspose.slides/ipresentation) ในตัวอย่างด้านล่าง แหล่งข้อมูลคือไฟล์ "pres.pptx" สำหรับตัวอย่างนี้ แหล่งข้อมูล ("pres.pptx" file) จะถูกล็อกตลอดอายุของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) กล่าวคือ ไม่สามารถเปลี่ยนแปลงหรือถูกลบโดยกระบวนการอื่นได้.

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | แหล่งข้อมูลจะถูกล็อกเฉพาะช่วงเวลาการทำงานของคอนสตรัคเตอร์ [IPresentation](../../com.aspose.slides/ipresentation) เท่านั้น. |
| [KeepLocked](#KeepLocked) | แหล่งข้อมูลจะถูกล็อกตลอดอายุของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) จนกว่าจะถูกทำลาย. |

### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

แหล่งข้อมูลจะถูกล็อกเฉพาะช่วงเวลาการทำงานของคอนสตรัคเตอร์ [IPresentation](../../com.aspose.slides/ipresentation) เท่านั้น.

--------------------

หาก ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) ถูกตั้งค่าเป็น false ทั้งหมด BLOB จะถูกโหลดเข้าสู่หน่วยความจำ มิฉะนั้นอาจใช้วิธีอื่นเช่นไฟล์ชั่วคราว.

--------------------

พฤติกรรมนี้ช้ากว่า [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) และหากเป็นไปได้ที่จะโอนความเป็นเจ้าของของแหล่งข้อมูลให้กับ [IPresentation](../../com.aspose.slides/ipresentation) ควรใช้ [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

แหล่งข้อมูลจะถูกล็อกตลอดอายุของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) จนกว่าจะถูกทำลาย.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) ต้องตั้งค่าเป็น true เพื่อใช้พฤติกรรมนี้ มิฉะนั้นจะเกิดข้อยกเว้น.

--------------------

พฤติกรรมนี้แนะนำ เนื่องจากเร็วกว่าและใช้หน่วยความจำน้อยกว่า [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).