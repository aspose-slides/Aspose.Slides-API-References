---
title: IXamlOutputSaver
second_title: Aspose.Slides for Java API Reference
description: Represents an output saver implementation for transfer data to the external storage.
type: docs
url: /th/com.aspose.slides/ixamloutputsaver/
---```
public interface IXamlOutputSaver
```

เป็นการนำเสนอการดำเนินการบันทึกผลลัพธ์เพื่อโอนข้อมูลไปยังที่เก็บภายนอก
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [save(String path, byte[] data)](#save-java.lang.String-byte---) | บันทึกอาเรย์ของไบต์ไปยังตำแหน่งปลายทาง |
### save(String path, byte[] data) {#save-java.lang.String-byte---}
```
public abstract void save(String path, byte[] data)
```

บันทึกอาเรย์ของไบต์ไปยังตำแหน่งปลายทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางปลายทาง |
| data | byte[] | ข้อมูลไบนารีสำหรับการบันทึกไปยังตำแหน่งปลายทาง |