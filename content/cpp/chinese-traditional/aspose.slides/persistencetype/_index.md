---
title: PersistenceType
second_title: Aspose.Slides for C++ API 參考
description: 指定用於儲存 ActiveX 控制項屬性的方法。
type: docs
weight: 6189
url: /zh-hant/aspose.slides/persistencetype/
---
## PersistenceType 列舉

指定用於儲存 ActiveX 控制項屬性的方法。

```cpp
enum class PersistenceType
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| NotDefined | -1 | 未指定持續性 ID。 |
| PersistPropertyBag | 0 | 指定使用基於屬性包的持久性來保存 ActiveX 控制項。基於屬性包的持久性透過一組名稱和值的配對來存儲 ActiveX 控制項，這些配對指定了由 ActiveX 控制項持久化的資料。 |
| PersistStream | 1 | 指定使用基於串流的持久性來保存 ActiveX 控制項，且此持久性不支援將 ActiveX 控制項初始化為預設狀態。 |
| PersistStreamInit | 2 | 指定使用基於串流的持久性來保存 ActiveX 控制項，且此持久性支援將 ActiveX 控制項初始化為預設狀態。 |
| PersistStorage | 3 | 指定使用基於儲存的持久性來保存 ActiveX 控制項。 |

## 另見

* 命名空間 [Aspose::Slides](../)
* 程式庫 [Aspose.Slides](../../)