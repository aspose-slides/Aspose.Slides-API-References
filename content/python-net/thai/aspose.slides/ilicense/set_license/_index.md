---
title: set_license method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
ให้การอนุญาตแก่คอมโพเนนต์.


```python
def set_license(self, license_name):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| license_name | **str** | สามารถเป็นชื่อไฟล์เต็มหรือสั้นหรือชื่อของทรัพยากรที่ฝังอยู่.<br/><br/>            ใช้สตริงว่างเพื่อสลับเป็นโหมดการประเมินผล. |

### หมายเหตุ

พยายามค้นหาไลเซนส์ในตำแหน่งต่อไปนี้:


1. เส้นทางที่ระบุโดยตรง.

2. โฟลเดอร์ของแอสเซมบลีคอมโพเนนต์.

3. โฟลเดอร์ของแอสเซมบลีที่เรียกใช้ของไคลเอนต์.

4. โฟลเดอร์ของแอสเซมบลีเริ่มต้น.

5. ทรัพยากรที่ฝังอยู่ในแอสเซมบลีที่เรียกใช้ของไคลเอนต์.

**หมายเหตุ:** บน .NET Compact Framework จะพยายามค้นหาไลเซนส์เฉพาะในตำแหน่งต่อไปนี้:


1. เส้นทางที่ระบุโดยตรง.

2. ทรัพยากรที่ฝังอยู่ในแอสเซมบลีที่เรียกใช้ของไคลเอนต์.


## set_license(self, stream) {#iorawiobase}
ให้การอนุญาตแก่คอมโพเนนต์.


```python
def set_license(self, stream):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมที่มีไลเซนส์อยู่. |

### หมายเหตุ

ใช้เมธอดนี้เพื่อโหลดไลเซนส์จากสตรีม.



### ดูเพิ่มเติม
* คลาส [`ILicense`](/slides/python-net/th/aspose.slides/ilicense)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)