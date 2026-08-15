---
title: FieldAttributes
second_title: Aspose.Slides for C++ API 參考文件
description: 已反射的欄位屬性。
type: docs
weight: 170
url: /zh-hant/system.reflection/fieldattributes/
---
## FieldAttributes enum

已反射的欄位屬性。

```cpp
enum class FieldAttributes
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| FieldAccessMask | 7 | 成員存取遮罩。使用此遮罩可取得可存取性資訊。 |
| PrivateScope | 0 | 不可參照的成員。 |
| Private | 1 | 私有成員。 |
| FamANDAssem | 2 | 私有且受組件範圍限制的成員。 |
| Assembly | 3 | 受組件範圍限制的成員。 |
| Family | 4 | 可由類型及其子類別存取的成員。 |
| FamORAssem | 5 | 可由類型、子類別及組件存取的成員。 |
| Public | 6 | 任何人皆可存取的成員。 |
| Static | 16 | 靜態成員，與實例成員相對。 |
| InitOnly | 32 | 只能在初始化時設定、之後不可變更的常數成員。 |
| Literal | 64 | 編譯時期的常數成員。 |
| NotSerialized | 128 | 未序列化的成員。 |
| SpecialName | 512 | 以下名稱之一的特殊欄位。 |
| PinvokeImpl | 8192 | 互操作轉發的實作。 |
| ReservedMask | 38144 | 僅供執行階段使用的保留旗標。 |
| RTSpecialName | 1024 | 執行階段應檢查名稱編碼。 |
| HasFieldMarshal | 4096 | 存在交叉編組資訊。 |
| HasDefault | 32768 | 存在預設值。 |
| HasFieldRVA | 256 | 存在 RVA。 |

## 另請參閱

* 命名空間 [System::Reflection](../)
* 函式庫 [Aspose.Slides](../../)