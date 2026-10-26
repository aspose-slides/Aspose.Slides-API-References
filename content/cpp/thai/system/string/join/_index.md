---
title: Join()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เชื่อมต่ออาเรย์โดยใช้สตริงเป็นตัวคั่น.
type: docs
weight: 846
url: /th/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) เมธอด


เชื่อมต่ออาร์เรย์โดยใช้สตริงเป็นตัวคั่น.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) เพื่อวางระหว่างองค์ประกอบของอาร์เรย์เมื่อทำการเชื่อมต่อ |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) ของส่วนที่จะเชื่อมต่อ |
| startIndex | int | ดัชนีแรกในอาร์เรย์ที่เริ่มการเชื่อมต่อจาก |
| count | int | จำนวนขององค์ประกอบในอาร์เรย์ที่จะเชื่อมต่อ. -1 หมายถึง 'จนกระทั่งอาร์เรย์สิ้นสุด' |

### Return Value

[String](../) แสดงถึงองค์ประกอบของอาร์เรย์ที่เชื่อมต่อ

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) เมธอด


เชื่อมต่ออาร์เรย์โดยใช้สตริงเป็นตัวคั่น.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) เพื่อวางระหว่างองค์ประกอบของอาร์เรย์เมื่อทำการเชื่อมต่อ |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView ของส่วนที่จะเชื่อมต่อ |
| startIndex | int | ดัชนีแรกในอาร์เรย์ที่เริ่มการเชื่อมต่อจาก |
| count | int | จำนวนขององค์ประกอบในอาร์เรย์ที่จะเชื่อมต่อ. -1 หมายถึง 'จนกระทั่งอาร์เรย์สิ้นสุด' |

### Return Value

[String](../) แสดงถึงองค์ประกอบของอาร์เรย์ที่เชื่อมต่อ

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) เมธอด


เชื่อมต่ออาร์เรย์โดยใช้สตริงเป็นตัวคั่น.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) เพื่อวางระหว่างองค์ประกอบของอาร์เรย์เมื่อทำการเชื่อมต่อ |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - วัตถุ enumerable ของส่วน |

### Return Value

[String](../) แสดงถึงส่วนที่เชื่อมต่อ

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) เมธอด


เชื่อมต่ออาร์เรย์โดยใช้สตริงเป็นตัวคั่น.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) เพื่อวางระหว่างองค์ประกอบของอาร์เรย์เมื่อทำการเชื่อมต่อ |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) ของส่วนที่จะเชื่อมต่อ |

### Return Value

[String](../) แสดงถึงส่วนที่เชื่อมต่อ

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../)
* คลาส [IEnumerable](../../../system.collections.generic/ienumerable/)
* คลาส [Object](../../object/)
* เนมส페스 [System](../../)
* ไลบรารี [Aspose.Slides](../../../)