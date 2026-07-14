---
title: LoadingStreamBehavior
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: java.io.InputStream ที่ส่งให้กับเมธอดถือเป็น Binary Large Object (BLOB) ดูรายละเอียด.
type: docs
url: /th/com.aspose.slides/loadingstreambehavior/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

java.io.InputStream ที่ส่งให้กับเมธอดถือเป็น Binary Large Object (BLOB) (ดูคำอธิบายของ [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) ค่าใน enumeration นี้ระบุว่า java.io.InputStream ควรได้รับการปฏิบัติเช่นไรเมื่อถูกส่งไปยังเมธอด ขึ้นอยู่กับความต้องการ สามารถทำการตัดสินใจที่แตกต่างกันเพื่อให้ได้ประสิทธิภาพที่ดีที่สุด
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | สตรีมจะถูกอ่านจนจบแล้วปล่อยออก - i.e. |
| [KeepLocked](#KeepLocked) | สตรีมจะถูกล็อคอยู่ภายในอ็อบเจ็กต์ [IPresentation](../../com.aspose.slides/ipresentation) , i.e. |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

สตรีมจะถูกอ่านจนจบแล้วปล่อยออก - i.e. จะรับประกันว่าสตรีมนี้จะไม่ถูกใช้โดยอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) ในอนาคต สามารถปิดได้โดยโค้ดของไคลเอนต์หรือใช้ในวิธีอื่นใดก็ได้

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // สามารถปิดสตรีมได้แล้ว, ไม่จำเป็นต้องใช้กับอ็อบเจ็กต์ "pres" อีกต่อไป.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

สตรีมจะถูกล็อคอยู่ภายในอ็อบเจ็กต์ [IPresentation](../../com.aspose.slides/ipresentation) , i.e. ความเป็นเจ้าของของสตรีมจะถูกโอนให้ โดยอ็อบเจ็กต์ [IPresentation](../../com.aspose.slides/ipresentation) จะรับผิดชอบในการทำลายสตรีมอย่างถูกต้องเมื่ออ็อบเจ็กต์นี้ถูกทำลายด้วยตัวมันเอง พฤติกรรมนี้มีประโยชน์อย่างยิ่งเมื่อคุณต้องการทำการซีเรียลไลซ์ไฟล์ BLOB ขนาดใหญ่ (เช่น วิดีโอหรือเสียงขนาดใหญ่ -ดูคำอธิบายของ [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) และต้องการป้องกันการโหลดไฟล์นี้เข้าสู่หน่วยความจำหรือปัญหาประสิทธิภาพอื่น ๆ คุณอาจเปิด java.io.FileInputStream สำหรับไฟล์นี้และส่งให้เมธอดโดยเลือก [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // คุณไม่ควรปิดสตรีมหรือโต้ตอบกับมันในวิธีอื่นใด, จะทำให้เกิดข้อผิดพลาดในเมธอด Save.
>    // fileStream จะถูกใช้สำหรับการบันทึก ซึ่งจะป้องกันการใช้หน่วยความจำสูง
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
