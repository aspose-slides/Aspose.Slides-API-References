---
title: HashData()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คำนวณค่าฮัชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริทึมที่กำหนด
type: docs
weight: 105
url: /th/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) method

คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริทึมที่ระบุ

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) เพื่อทำแฮช |
| offset | **int32_t** | ออฟเซ็ตใน **data** |
| count | **int32_t** | จำนวนไบต์ที่จะทำแฮช |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | อัลกอริทึมแฮช |

### Return Value

ข้อมูลที่ทำแฮชแล้ว

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) method

คำนวณค่าแฮชของสตรีมไบนารีที่ระบุโดยใช้แฮชอัลกอริทึมที่ระบุ

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | สตรีมไบนารีที่จะทำแฮช |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | อัลกอริทึมแฮช |

### Return Value

ข้อมูลที่ทำแฮชแล้ว

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)