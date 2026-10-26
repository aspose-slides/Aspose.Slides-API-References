---
title: set_license method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
กำหนดใบอนุญาตให้กับคอมโพเนนต์.


```python
def set_license(self, license_name):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| license_name | **str** | สามารถเป็นชื่อไฟล์เต็มหรือสั้น หรือชื่อของทรัพยากรที่ฝังอยู่.<br/><br/>ใช้สตริงว่างเพื่อสลับไปยังโหมดประเมินผล. |

### หมายเหตุ

พยายามค้นหาใบอนุญาตในตำแหน่งต่อไปนี้:


1. เส้นทางที่ระบุโดยตรง.

2. โฟลเดอร์ของแอสเซมบลี่คอมโพเนนต์.

3. โฟลเดอร์ของแอสเซมบลี่ที่เรียกใช้โดยไคลเอนต์.

4. โฟลเดอร์ของแอสเซมบลี่เริ่มต้น.

5. ทรัพยากรที่ฝังอยู่ในแอสเซมบลี่ที่เรียกใช้โดยไคลเอนต์.

**หมายเหตุ:** บน .NET Compact Framework จะพยายามค้นหาใบอนุญาตเฉพาะในตำแหน่งเหล่านี้:


1. เส้นทางที่ระบุโดยตรง.

2. ทรัพยากรที่ฝังอยู่ในแอสเซมบลี่ที่เรียกใช้โดยไคลเอนต์.

## set_license(self, stream) {#iorawiobase}
กำหนดใบอนุญาตให้กับคอมโพเนนต์.


```python
def set_license(self, stream):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมที่มีใบอนุญาต. |

### หมายเหตุ

ใช้เมธอดนี้เพื่อโหลดใบอนุญาตจากสตรีม.



### ดูเพิ่มเติม
* คลาส [`License`](/slides/python-net/th/aspose.slides/license)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)