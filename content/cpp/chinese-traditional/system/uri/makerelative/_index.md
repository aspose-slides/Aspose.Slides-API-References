---
title: MakeRelative()
second_title: Aspose.Slides for C++ API 參考
description: 判斷兩個 Uri 實例之間的差異。
type: docs
weight: 365
url: /zh-hant/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) 方法

判斷兩個 [Uri](../) 實例之間的差異。

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 要與目前的 URI 比較的 URI |

### 返回值

如果目前物件與 **toUri** 所表示的 URI 的主機名稱與協議相同，則此方法會回傳一個代表相對 [Uri](../) 的 [String](../../string/)，當將其附加到目前的 URI 實例時，會得到 **toUri**。如果主機名稱或協議不同，則此方法會回傳一個代表 **uri** 參數的 [String](../../string/)。

## 另見

* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [Uri](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)