---
title: BitVector32
second_title: Aspose.Slides for C++ API 參考
description: 提供簡單且輕量的位元向量，並可輕鬆以整數或布林方式存取 32 位元儲存空間。
type: docs
weight: 1
url: /zh-hant/system.collections.specialized/bitvector32/
---
## BitVector32 類別

Provides a simple light bit vector with easy integer or [Boolean](../../system/boolean/) access to a 32 bit storage.

```cpp
class BitVector32
```

## 方法

| 方法 | 說明 |
| --- | --- |
|  [BitVector32](./bitvector32/)() | 初始化 [BitVector32](./) 的新空實例。 |
|  [BitVector32](./bitvector32/)(**int32_t**) | 使用指定的內部資料初始化 [BitVector32](./) 結構的新實例。 |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | 使用指定值中的資訊初始化 [BitVector32](./) 結構的新實例。 |
| static **int32_t** [CreateMask](./createmask/)() | 建立系列中的第一個遮罩。 |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | 建立系列中的下一個遮罩。 |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | 使用指定的最大值建立系列中的第一個區段。 |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | 使用指定的最大值建立系列中的下一個區段。 |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | 判斷指定的物件是否與目前物件相同。 |
| **int32_t** [get_Data](./get_data/)() | 回傳此位向量儲存的原始資料… |
| **int32_t** [GetHashCode](./gethashcode/)() const | 回傳目前物件的雜湊碼。 |
| **bool** [idx_get](./idx_get/)(**int32_t**) | 取得一個值，指示所有指定的位元是否已設定。 |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | 取得指定區段的值。 |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | 設定一個值，指示所有指定的位元是否已設定。 |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | 設定指定區段的值。 |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | 將值參數所代表的值轉換為字串。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 將目前物件所代表的值轉換為字串。 |

## 另請參見

* 命名空間 [System::Collections::Specialized](../)
* 函式庫 [Aspose.Slides](../../)