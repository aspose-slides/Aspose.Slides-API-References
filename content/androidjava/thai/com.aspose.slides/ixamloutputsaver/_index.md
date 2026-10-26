---
title: IXamlOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an output saver implementation for transfer data to the external storage.
type: docs
url: /th/com.aspose.slides/ixamloutputsaver/
---```
public interface IXamlOutputSaver
```

แสดงการใช้งานตัวจัดเก็บผลลัพธ์สำหรับการโอนย้ายข้อมูลไปยังที่จัดเก็บภายนอก.
## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [save(String path, byte[] data)](#save-java.lang.String-byte---) | Saves a bytes array to a destination location. |
### save(String path, byte[] data) {#save-java.lang.String-byte---}
```
public abstract void save(String path, byte[] data)
```

บันทึกอาร์เรย์ของไบต์ไปยังตำแหน่งปลายทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางปลายทาง |
| data | byte[] | ข้อมูลไบต์สำหรับบันทึกไปยังตำแหน่งปลายทาง |