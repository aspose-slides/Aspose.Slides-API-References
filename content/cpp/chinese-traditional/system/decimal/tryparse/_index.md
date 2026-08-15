---
title: TryParse()
second_title: Aspose.Slides C++ API 參考文件
description: 將包含數字字串表示的指定字串轉換為等效的 Decimal 值。
type: docs
weight: 482
url: /zh-hant/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) 方法


將包含數字字串表示的指定字串轉換為等效的 [Decimal](../) 值。

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| result | [Decimal](../)\& | 指向 [Decimal](../) 變數的參考，用於放置轉換結果 |

### 回傳值

如果轉換成功則傳回 true，否則傳回 false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) 方法


將包含數字字串表示的指定字串，使用提供的格式資訊和數字樣式，轉換為等效的 [Decimal](../) 值。

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的位元組合，用於指定允許的數字字串表示樣式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |
| result | [Decimal](../)\& | 輸出參數；包含轉換結果 |

### 回傳值

如果轉換成功則傳回 true，否則傳回 false

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)