---
title: LoadingStreamBehavior
second_title: Aspose.Slides สำหรับ Java API Reference
description: java.io.InputStream ที่ส่งให้เมธอดจะถือเป็น Binary Large Object (BLOB) ดู description.
type: docs
url: /th/com.aspose.slides/loadingstreambehavior/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

java.io.InputStream ที่ส่งให้เมธอดจะถือเป็น Binary Large Object (BLOB) (ดู [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) description). ค่าของ enumeration นี้ระบุว่า java.io.InputStream ควรได้รับการจัดการอย่างไรเมื่อถูกส่งให้เมธอด ตามความต้องการอาจมีการตัดสินใจต่าง ๆ เพื่อให้ได้ประสิทธิภาพที่ดีที่สุด
## ฟิลด์

| Field | Description |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | สตรีมจะถูกอ่านจนจบแล้วจึงปล่อยออก - i.e. |
| [KeepLocked](#KeepLocked) | สตรีมจะถูกล็อคภายในวัตถุ [IPresentation](../../com.aspose.slides/ipresentation) , i.e. |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

สตรีมจะถูกอ่านจนจบแล้วจึงปล่อยออก - i.e. จะรับประกันว่าสตรีมนี้จะไม่ถูกใช้โดยอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) ในอนาคต สามารถปิดได้โดยโค้ดของไคลเอนต์หรือใช้ในวิธีอื่นใดก็ได้.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // สามารถปิดสตรีมได้แล้ว ไม่จำเป็นต้องใช้กับวัตถุ "pres" อีกต่อไป.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

สตรีมจะถูกล็อคภายในวัตถุ [IPresentation](../../com.aspose.slides/ipresentation) , i.e. ความเป็นเจ้าของสตรีมจะถูกย้ายไป วัตถุ [IPresentation](../../com.aspose.slides/ipresentation) จะรับผิดชอบในการจัดการปล่อยสตรีมอย่างถูกต้องเมื่อวัตถุนี้ถูกปล่อยเอง พฤติกรรมนี้เป็นประโยชน์อย่างยิ่งเมื่อคุณต้องทำการซีเรียลไลซ์ไฟล์ BLOB ขนาดใหญ่ (เช่นวิดีโอหรือเสียงขนาดใหญ่ -see [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) description) และต้องการป้องกันการโหลดไฟล์นี้เข้าสู่หน่วยความจำหรือปัญหาประสิทธิภาพอื่น คุณอาจเปิด java.io.FileInputStream สำหรับไฟล์นี้และส่งให้เมธอดโดยเลือก [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // คุณไม่ควรปิดสตรีมหรือโต้ตอบกับมันในวิธีอื่นใด เนื่องจากจะทำให้เกิดข้อผิดพลาดในเมธอด Save.
>    // fileStream จะถูกใช้สำหรับการบันทึก ซึ่งจะป้องกันการใช้หน่วยความจำสูง
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
