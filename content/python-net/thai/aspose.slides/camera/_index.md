---
title: Camera class
second_title: อ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/camera/
---
## คลาส Camera

เป็นตัวแทนของ Camera.

**Inheritance:**[`Camera`](/slides/python-net/th/aspose.slides/camera) → [`PVIObject`](/slides/python-net/th/aspose.slides/pviobject)

ประเภท Camera เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/th/aspose.slides/camera/camera_type/) | ประเภท Camera.<br/>            อ่าน/เขียน [`CameraPresetType`](/slides/python-net/th/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/th/aspose.slides/camera/field_of_view_angle/) | Camera FOV (0-180 deg, มุมมอง).<br/>            อ่าน/เขียน **float**. |
| [`zoom`](/slides/python-net/th/aspose.slides/camera/zoom/) | การซูมของ Camera (ค่าบวกเป็นเปอร์เซ็นต์).<br/>            อ่าน/เขียน **float**. |
| [`slide`](/slides/python-net/th/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/camera/presentation/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/th/aspose.slides/camera/set_rotation/#float-float-float) | การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด<br/>            พิกัดลองจิจูด, และการหมุนรอบแกน <br/>            เช่นเดียวกับพิกัดละติจูดและลองจิจูด.<br/>            หากค่าพิกัดใดเป็น float.NaN การหมุนทั้งหมดจะไม่กำหนด. |
| [`get_rotation(self)`](/slides/python-net/th/aspose.slides/camera/get_rotation/#) | การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด<br/>            พิกัดลองจิจูด, และการหมุนรอบแกน <br/>            เช่นเดียวกับพิกัดละติจูดและลองจิจูด.<br/>            รายการแรกในอาร์เรย์ผลลัพธ์ - ละติจูด, รายการที่สอง - ลองจิจูด, รายการที่สาม - การหมุน.<br/>            คืนค่า None หากไม่มีการหมุนที่กำหนด. |


### ดูเพิ่มเติม
* คลาส [`Camera`](/slides/python-net/th/aspose.slides/camera)
* คลาส [`PVIObject`](/slides/python-net/th/aspose.slides/pviobject)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)