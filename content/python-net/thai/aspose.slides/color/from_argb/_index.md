---
title: from_argb method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
สร้างสีจากค่า ARGB 32-บิต

### คืนค่า

สีที่สร้างจากค่าที่ระบุ



```python
@staticmethod
def from_argb(argb):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| argb | **int** | ค่าที่ระบุค่า ARGB 32-บิต (มีเครื่องหมายหรือไม่มีเครื่องหมาย) |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **ValueError** | ค่าของส่วนประกอบน้อยกว่า 0 หรือมากกว่า 255 |
| **TypeError** | จำนวนหรือประเภทของอาร์กิวเมนต์ไม่ถูกต้อง |


## from_argb(alpha, base_color) {#int-color}
สร้างสีจากค่าอัลฟาที่ระบุและสีฐาน

### คืนค่า

สีที่สร้างจากค่าที่ระบุ



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alpha | **int** | ค่าของส่วนประกอบอัลฟา ค่าที่ถูกต้องคือ 0 ถึง 255 |
| base_color | [`Color`](/slides/python-net/th/aspose.slides/color) | สีที่จะใช้สร้างสีใหม่ |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **ValueError** | ค่าของส่วนประกอบน้อยกว่า 0 หรือมากกว่า 255 |
| **TypeError** | จำนวนหรือประเภทของอาร์กิวเมนต์ไม่ถูกต้อง |


## from_argb(red, green, blue) {#int-int-int}
สร้างสีทึบ (alpha เป็น 255) จากค่าตำแหน่งสีแดง เขียว และน้ำเงินที่ระบุ

### คืนค่า

สีที่สร้างจากค่าที่ระบุ



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| red | **int** | ค่าของส่วนประกอบสีแดง ค่าที่ถูกต้องคือ 0 ถึง 255 |
| green | **int** | ค่าของส่วนประกอบสีเขียว ค่าที่ถูกต้องคือ 0 ถึง 255 |
| blue | **int** | ค่าของส่วนประกอบสีน้ำเงิน ค่าที่ถูกต้องคือ 0 ถึง 255 |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **ValueError** | ค่าของส่วนประกอบน้อยกว่า 0 หรือมากกว่า 255 |
| **TypeError** | จำนวนหรือประเภทของอาร์กิวเมนต์ไม่ถูกต้อง |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
สร้างสีจากค่าคอมโพเนนต์ ARGB ทั้งสี่ (alpha, red, green, และ blue)

### คืนค่า

สีที่สร้างจากค่าที่ระบุ



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alpha | **int** | ค่าของส่วนประกอบอัลฟา ค่าที่ถูกต้องคือ 0 ถึง 255 |
| red | **int** | ค่าของส่วนประกอบสีแดง ค่าที่ถูกต้องคือ 0 ถึง 255 |
| green | **int** | ค่าของส่วนประกอบสีเขียว ค่าที่ถูกต้องคือ 0 ถึง 255 |
| blue | **int** | ค่าของส่วนประกอบสีน้ำเงิน ค่าที่ถูกต้องคือ 0 ถึง 255 |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **ValueError** | ค่าของส่วนประกอบน้อยกว่า 0 หรือมากกว่า 255 |
| **TypeError** | จำนวนหรือประเภทของอาร์กิวเมนต์ไม่ถูกต้อง |



### ดูเพิ่มเติม
* คลาส [`Color`](/slides/python-net/th/aspose.slides/color)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)