---
title: BindingFlags
second_title: Aspose.Slides for C++ API 參考
description: 定義成員和類型的查找模式與繫結。
type: docs
weight: 157
url: /zh-hant/system.reflection/bindingflags/
---
## BindingFlags 列舉

定義成員和類型的查找模式與繫結。

```cpp
enum class BindingFlags
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Default | 0 | 沒有特殊選項。 |
| IgnoreCase | 1 | 在尋找項目時忽略名稱大小寫。 |
| DeclaredOnly | 2 | 僅搜尋在類型中宣告而非基底類型中的成員。 |
| Instance | 4 | 搜尋實例成員。 |
| Static | 8 | 搜尋靜態成員。 |
| Public | 16 | 搜尋公開成員。 |
| NonPublic | 32 | 搜尋非公開成員。 |
| FlattenHierarchy | 64 | 搜尋基底類型的公開與受保護的靜態成員。 |
| InvokeMethod | 256 | 呼叫方法。 |
| CreateInstance | 512 | 建立反射類型的實例。 |
| GetField | 1024 | 取得欄位值。 |
| SetField | 2048 | 設定欄位值。 |
| GetProperty | 4096 | 取得屬性值。 |
| SetProperty | 8192 | 設定屬性值。 |
| PutDispProperty | 16384 | 設定 COM 屬性。 |
| PutRefDispProperty | 32768 | 設定 COM 參考屬性。 |
| ExactBinding | 65536 | 型別繫結必須精確，且不得有任何型別變更。 |
| SuppressChangeType | 131072 | 不支援。 |
| OptionalParamBinding | 262144 | 根據參數數量選擇重載。 |
| IgnoreReturn | 16777216 | 忽略 COM 互操作的返回值。 |

## 另請參閱

* 命名空間 [System::Reflection](../)
* 函式庫 [Aspose.Slides](../../)