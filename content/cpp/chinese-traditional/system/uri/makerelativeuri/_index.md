---
title: MakeRelativeUri()
second_title: Aspose.Slides for C++ API 參考
description: 確定目前物件與指定的 Uri 物件所代表的 URI 之差異。
type: docs
weight: 352
url: /zh-hant/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) 方法

判斷目前物件與指定的 [Uri](../) 物件所代表的 URI 之差異。

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The comparand |

### 回傳值

如果目前物件與 **toUri** 所代表的 URI 之主機名稱與協議相同，則此方法會傳回一個相對 [Uri](../)，將其附加於目前的 URI 實例後即可得到 **toUri**。如果主機名稱或協議不同，則此方法會傳回一個 [Uri](../) 物件，代表 **uri** 參數。

## 另請參閱

* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [Uri](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)