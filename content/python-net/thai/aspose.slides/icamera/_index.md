---
title: ICamera class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/icamera/
---
## ICamera คลาส

แสดงถึงกล้อง.

ประเภท ICamera เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/th/aspose.slides/icamera/camera_type/) | ประเภทกล้อง<br/>            อ่าน/เขียน [`CameraPresetType`](/slides/python-net/th/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/th/aspose.slides/icamera/field_of_view_angle/) | FOV ของกล้อง (0-180 deg, field of View)<br/>            อ่าน/เขียน **float**. |
| [`zoom`](/slides/python-net/th/aspose.slides/icamera/zoom/) | การขยายกล้อง (ค่าบวกเป็นเปอร์เซ็นต์)<br/>            อ่าน/เขียน **float**. |

## วิธีการ

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/th/aspose.slides/icamera/set_rotation/#float-float-float) | การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด<br/>            พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด.<br/>            หากค่าพิกัดใดเป็น float.NaN การหมุนทั้งหมดจะไม่กำหนด. |
| [`get_rotation(self)`](/slides/python-net/th/aspose.slides/icamera/get_rotation/#) | การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด<br/>            พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด.<br/>            สมาชิกแรกในอาร์เรย์ที่คืนค่า - ละติจูด, ตัวที่สอง - ลองจิจูด, ตัวที่สาม - การหมุน.<br/>            คืนค่า None หากไม่มีการหมุนใด ๆ กำหนด. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)