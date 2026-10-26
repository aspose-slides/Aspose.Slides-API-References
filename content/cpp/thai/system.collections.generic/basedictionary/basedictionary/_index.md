---
title: BaseDictionary()
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ C++
description: สร้างโครงสร้างข้อมูลเปล่า.
type: docs
weight: 14
url: /th/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() คอนสตรัคเตอร์

Creates empty data structure.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) คอนสตรา‍คเตอร์

Forwarding constructor to push arguments into underlying map constructor.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Args | Types of arguments to forward to map. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| args | int | Arguments to forward to underlying map. |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) คอนสตรา‍คเตอร์

Copying constructor.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Args | Types of map constructor arguments. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) เพื่อคัดลอกข้อมูลจาก. |
| args | const Args\&... | Arguments to forward to underlying map constructor. |

## BaseDictionary::BaseDictionary(BaseType *) คอนสตรา‍คเตอร์

Copying constructor.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) เพื่อคัดลอกข้อมูลจาก. |

## ดูเพิ่มเติม

* Typedef [BaseType](../basetype/)
* คลาส [BaseDictionary](../)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)