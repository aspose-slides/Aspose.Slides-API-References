---
title: Create()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างการดำเนินการอัลกอริธึม ECDSA เริ่มต้น.
type: docs
weight: 131
url: /th/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() method


สร้างการดำเนินการอัลกอริธึม ECDSA เริ่มต้น

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```


### Return Value

อ็อบเจ็กต์อัลกอริธึม ECDSA

## ECDsa::Create(const ECCurve\&) method


สร้างการดำเนินการอัลกอริธึม ECDSA เริ่มต้นพร้อมคีย์ที่สร้างใหม่ตามเส้นโค้งที่ระบุ

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | เส้นโค้งที่ใช้สำหรับการสร้างคีย์ |

### Return Value

อ็อบเจ็กต์อัลกอริธึม ECDSA

## ECDsa::Create(const ECParameters\&) method


สร้างการดำเนินการอัลกอริธึม ECDSA เริ่มต้นโดยใช้พารามิเตอร์ที่ระบุ

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | พารามิเตอร์ที่แสดงถึงคีย์ |

### Return Value

อ็อบเจ็กต์อัลกอริธึม ECDSA

## ECDsa::Create(const String\&) method


สร้างการดำเนินการอัลกอริธึม ECDSA ที่ระบุ

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | ชื่ออัลกอริธึม |

### Return Value

อ็อบเจ็กต์อัลกอริธึม ECDSA

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ECDsa](../)
* คลาส [String](../../../system/string/)
* โครงสร้าง [ECCurve](../../eccurve/)
* โครงสร้าง [ECParameters](../../ecparameters/)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)