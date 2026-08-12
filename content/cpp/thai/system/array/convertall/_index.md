---
title: ConvertAll()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: สร้างอ็อบเจ็กต์ Array ใหม่และเติมด้วยองค์ประกอบของอาร์เรย์ที่ระบุซึ่งแปลงเป็นประเภท OutputType โดยใช้ตัวมอบหมาย converter ที่ระบุ
type: docs
weight: 625
url: /th/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) method

สร้างอ็อบเจ็กต์ [Array](../) ใหม่และเติมด้วยองค์ประกอบของอาร์เรย์ที่ระบุซึ่งแปลงเป็นประเภท **OutputType** โดยใช้ตัวมอบหมาย converter ที่ระบุ

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| InputType | ประเภทขององค์ประกอบของอาร์เรย์อินพุต |
| OutputType | ประเภทขององค์ประกอบของอาร์เรย์ผลลัพธ์ |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | อ็อบเจ็กต์ [Array](../) |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | อ็อบเจ็กต์ Converter ที่ใช้ในการแปลงแต่ละองค์ประกอบของอาร์เรย์อินพุตเป็นค่าที่เทียบเท่าของประเภท **OutputType** |

### ค่าผลลัพธ์

อาร์เรย์ใหม่ที่มีค่าของประเภท **OutputType** เทียบเท่ากับค่าของ `input_array`

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) method

สร้างอ็อบเจ็กต์ [Array](../) ใหม่และเติมด้วยองค์ประกอบของอาร์เรย์ที่ระบุซึ่งแปลงเป็นประเภท **OutputType** โดยใช้ฟังก์ชันอ็อบเจ็กต์ converter ที่ระบุ

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| InputType | ประเภทขององค์ประกอบของอาร์เรย์อินพุต |
| OutputType | ประเภทขององค์ประกอบของอาร์เรย์ผลลัพธ์ |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | อ็อบเจ็กต์ [Array](../) |
| converter | std::function\<OutputType(InputType)> | อ็อบเจ็กต์ฟังก์ชันที่ใช้ในการแปลงแต่ละองค์ประกอบของอาร์เรย์อินพุตเป็นค่าที่เทียบเท่าของประเภท **OutputType** |

### ค่าผลลัพธ์

อาร์เรย์ใหม่ที่มีค่าของประเภท **OutputType** เทียบเท่ากับค่าของ `input_array`

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)